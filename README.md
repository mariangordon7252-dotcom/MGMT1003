# PHIL1005 期末复习

ANU PHIL1005 期末复习 App。整个 App 就是一个网页，没有服务器、不需要登录。

## 上传到 GitHub 并开启网页（只需做一次）

1. 登录 github.com，右上角 **+ → New repository**。
   - 名字随便起，比如 `phil1005-review`。
   - 选 **Public**。免费账号的 GitHub Pages 只支持公开仓库。
2. 建好后点 **uploading an existing file**。把这个文件夹里的所有文件拖进去，然后点 **Commit changes**：
   - `index.html`
   - `sw.js`
   - `manifest.webmanifest`
   - `icon-180.png`、`icon-192.png`、`icon-512.png`
   - `README.md`
   - `.nojekyll`：这是隐藏文件。Windows 上看不到的话，在文件资源管理器里打开「查看 → 显示 → 隐藏的项目」。漏传也能用。
3. 仓库页面点 **Settings → Pages**。
   - **Source** 选 **Deploy from a branch**。
   - **Branch** 选 `main`、`/ (root)`，点 **Save**。
4. 等 1–2 分钟，刷新这一页。顶部会出现网址，形如 `https://你的用户名.github.io/phil1005-review/`。

## 装到 iPhone 上

1. 用 **Safari** 打开上面的网址。必须用 Safari，别的浏览器加不到主屏幕。
2. 点底部的 **分享** 按钮，选 **添加到主屏幕**，再点 **添加**。
3. 主屏幕上会出现珊瑚色的「PHIL1005」图标，点开就是全屏 App。
4. 第一次打开时要联网。打开过一次之后，没网也能用。

## 注意

- **做题记录存在手机本机。** 只在这个 App 里有效，不会上传。删除 App 图标或清除 Safari 网站数据会清掉记录。
  - 之前在 HTML Viewer 里的进度不会自动带过来。
- **更新内容：** 在 GitHub 仓库里重新上传新的 `index.html` 和 `sw.js`，覆盖旧文件。手机联网打开 App 一次就会自动换成新版，关掉再打开一次就能看到。
- **公开仓库谁都能看到。** 仓库里只有复习 App 本身，没有课程原始讲义，也没有个人作业。
