# Thesis 每日进度网页 / Thesis Daily Progress Website

## 项目简介 / Overview

中文：这是一个纯静态网页，用来记录论文每日进度。主文件是 `index.html`，不需要后端服务器。

English: This is a static website for tracking daily thesis progress. The main file is `index.html`, and no backend server is required.

## 当前公网链接 / Public Links

中文：GitHub Pages 公开访问地址：

English: Public GitHub Pages URL:

https://z2535045374-cyber.github.io/thesis-progress-web/

中文：PageDrop 临时备份地址：

English: Temporary PageDrop backup URL:

https://pagedrop.dev/s/iPBzYGSx

## 使用方式 / How To Use

中文：打开网页后，填写日期、完成情况、标题、今日任务和备注，也可以上传当天完成的文件，然后点击“保存记录”。记录和附件会显示在右侧历史列表中。

English: Open the website, enter the date, status, title, today's tasks, and notes, optionally upload the files completed that day, then click "Save Entry". Saved entries and attachments will appear in the history list on the right.

中文：网页支持中英文切换，也支持导出 JSON、导入 JSON、下载 CSV 和下载包含附件的 ZIP 记录包。

English: The website supports Chinese/English switching, JSON export, JSON import, CSV download, and ZIP bundle download with attachments.

## 数据说明 / Data Notes

中文：当前记录保存在每个访问者自己的浏览器 `localStorage` 中。别人打开公开链接后可以使用网页，但不会自动看到你电脑浏览器里已经保存的历史记录。

English: Entries are currently stored in each visitor's own browser `localStorage`. Other people can open and use the public website, but they will not automatically see the history saved in your browser.

中文：附件也会保存在浏览器本地空间里。较大的文件可能超过浏览器存储限制，建议保存论文草稿、截图、小型数据文件等轻量附件。

English: Attachments are also stored in the browser's local storage. Large files may exceed browser storage limits, so this works best for thesis drafts, screenshots, small data files, and other lightweight attachments.

中文：如果需要多人看到同一份进度，需要把数据接到在线数据库，或改成共享的静态数据文件。

English: If multiple people need to see the same shared progress records, the project should be connected to an online database or changed to use a shared static data file.

## 发布方式 / Deployment

中文：当前版本已经发布到 GitHub Pages，并从 `main` 分支的根目录构建。因为本项目没有后端，直接发布 `index.html` 即可。

English: The current version is deployed with GitHub Pages and built from the root of the `main` branch. Because this project has no backend, publishing `index.html` is enough.

中文：PageDrop 备份站点的 ID 和删除/更新 token 保存在本机的 `.pagedrop.json` 中，并已被 `.gitignore` 忽略。

English: The PageDrop backup site's ID and delete/update token are stored locally in `.pagedrop.json`, which is ignored by `.gitignore`.
