# GUI APP

Go 没有官方 GUI 方案，所有库都是三条路线的妥协：WebView + Go 后端、纯 Go 自绘、cgo 绑定原生控件。
先定路线，再定库。

## WebView + Go backend

- [wails](https://github.com/wailsapp/wails) – Go 后端 + 系统 WebView（WKWebView / WebView2 / WebKitGTK），前端用 HTML/CSS/JS；支持原生菜单、托盘、拖拽、系统对话框，自带打包 CLI。v3 已稳定。
- [webview](https://github.com/webview/webview) – 极小的窗口 + WebView 绑定，其余全部自己做。
- [lorca](https://github.com/zserge/lorca) – 复用本机 Chrome，通过 DevTools Protocol 通信。已停更。

## Pure Go self-drawn

- [fyne](https://fyne.io/fyne) – 组件齐全的 Material 风格 toolkit，桌面 + 移动端一套代码。注意默认字体不含 CJK，中文需自行嵌入。
- [gio](https://gioui.org) – Immediate mode + 自研 GPU 渲染管线，启动快、内存低、二进制小，可跑桌面 / 移动 / WASM。无 widget 库，适合自绘界面与数据可视化。
- [cogentcore](https://github.com/cogentcore/core) – 纯 Go，自带 2D/3D，一套代码跑桌面 + web。pre-v1，API 仍会变动。
- [ebiten](https://github.com/hajimehoshi/ebiten) – 2D 游戏引擎，做画布 / 节点编辑器 / 实时渲染面板比 GUI 库更顺手。

## Native bindings (cgo)

- [gotk4](https://github.com/diamondburned/gotk4) – GTK4 绑定，仍在活跃维护。
- [walk](https://github.com/lxn/walk) – Windows 原生 Win32 控件，已停更但仍是可用的薄封装。
- [cimgui-go](https://github.com/AllenDang/cimgui-go) – Dear ImGui 绑定，调试面板 / 内部工具的天花板。

## 通病

- **中文**：CJK 字体与输入法在自绘路线上都要手工处理。
- **无障碍**：除 WebView 路线外基本空白，有合规要求就别选自绘。
- **goroutine 与 UI 线程**：都需手动切回 UI 线程（Fyne 的 `fyne.Do`、Wails 的 Events、Gio 的 Invalidate）。
- **分发**：macOS 公证与 Windows 代码签名要自己搞定，Gio 还需手工处理 `.app` 结构与 manifest。

## Resources

- [Wails 文档](https://wails.io/docs/)
- [Fyne 文档](https://docs.fyne.io/)
- [Gio 示例集](https://github.com/gioui/gio-x)
