# Pocket Kit · 小工具箱

独立于根目录个人主页的小型效率工具，部署地址：

https://jin66yue-arch.github.io/my-homepage/app/

## 文件说明

- `index.html`：界面、启动动画和待办/倒计时/笔记/文本工具功能。
- `manifest.json`：PWA 应用名称、启动路径、显示方式等安装设置。
- `sw.js`：Service Worker 与离线缓存逻辑。
- `icons/icon.svg`：应用图标。

## 修改注意事项

- 根目录的 `index.html` 是个人主页；这里的 `app/index.html` 才是小工具箱。
- 保持 `manifest.json`、`sw.js` 和图标路径有效。
- 修改离线资源后，如有需要，更新 `sw.js` 中的缓存版本号，帮助浏览器加载新版本。
- 任务、笔记和倒计时保存在当前浏览器的本地存储中，不会自动同步到其他设备。
