# Thesis 每日进度网页

这是一个纯静态网页，主文件是 `index.html`。

## 当前公网链接

GitHub Pages：

https://z2535045374-cyber.github.io/thesis-progress-web/

临时 PageDrop 备份：

https://pagedrop.dev/s/iPBzYGSx

## 临时公网预览

如果需要马上把本地页面分享给别人，可以启动本地静态服务器，再用 Cloudflare Tunnel 生成公开链接。这个链接只有在当前电脑保持联网、服务保持运行时可用。

## 永久公开发布

要获得长期可用的公开链接，推荐发布到 GitHub Pages、Netlify、Vercel 或 Cloudflare Pages。因为本项目没有后端，直接把 `index.html` 发布为静态站点即可。

当前版本已经发布到 GitHub Pages。PageDrop 备份站点的 ID 和删除/更新 token 保存在本机的 `.pagedrop.json` 中，并已被 `.gitignore` 忽略。

注意：当前记录保存在每个访问者自己的浏览器 `localStorage` 中。别人打开公开链接后能使用网页，但不会自动看到你电脑浏览器里已经保存的历史记录。若需要多人看到同一份进度，需要把数据接到在线数据库或改成静态数据文件。
