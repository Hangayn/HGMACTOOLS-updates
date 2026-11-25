# HG MAC TOOLS

随手写的一个 macOS 小工具：截图、录屏、改两张图，扔菜单栏里随用随取。没打算做成大软件，纯自用向。

- 区域 / 全屏截图，截完能直接画框、画圈、箭头、铅笔、文字
- 拖选区时停一下会冒出放大镜，能看到起点/终点像素坐标；框出来之后还能拖四边四角微调，或者捏住中间的小圆点整块挪
- 录屏：整屏或区域，可选系统声音 + 麦克风（系统声音要 macOS 15 起）
- 菜单栏杂货铺：网络信息、隐藏文件开关、重启 Finder、开机自启
- 图标随你换：斑斑 / 包乔治 / 黑黑 / 胡子，或者上传自己的方形 PNG
- 几套半透明暗色主题
- 自带更新器：点一下「检查更新」，它自己下载 → 校验 sha256 → 替换 → 重启

## 下载

当前版本：**[HG-MAC-TOOLS-1.8.0-universal.zip](./HG-MAC-TOOLS-1.8.0-universal.zip)**（2.6 MB）

1. 解压，把 `HG MAC TOOLS.app` 拖进「应用程序」
2. 第一次打开若提示「无法验证开发者」，右键 →「打开」即可（自签名，没有苹果开发者证书）
3. 要求 macOS 12.3+，Intel / Apple Silicon 通用

版本号以 [update.json](./update.json) 为准，App 里的「检查更新」也是读它。

---

# HG MAC TOOLS (English)

A tiny macOS utility I wrote for myself: screenshots, screen recording, and a few menu bar conveniences. Not trying to be a big app.

- Region / full-screen capture, annotate right on the shot (rect, circle, arrow, pencil, text)
- Pause while dragging and a magnifier shows up with start/end pixel coordinates; the frame can then be resized from edges/corners or moved by its center handle
- Screen recording: full screen or a region, with system audio + microphone (system audio needs macOS 15+)
- Menu bar extras: network info, toggle hidden files, restart Finder, launch at login
- Swappable app icon (presets or your own square PNG)
- A few translucent dark themes
- Built-in updater: one click — it downloads, verifies the sha256, replaces itself and relaunches

## Download

Current build: **[HG-MAC-TOOLS-1.8.0-universal.zip](./HG-MAC-TOOLS-1.8.0-universal.zip)** (2.6 MB)

Unzip, drag `HG MAC TOOLS.app` into Applications. If macOS complains it cannot verify the developer, right-click → Open (the app is self-signed, no Apple Developer certificate). Requires macOS 12.3+, universal (Intel + Apple Silicon).

The version of record is [update.json](./update.json) — the in-app "检查更新 / Check for Updates" reads it too.
