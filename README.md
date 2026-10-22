# Jinyue · Personal Website

这是 Jinyue 的个人网站仓库，使用 GitHub Pages 发布。

## 在线页面

- **个人主页**：https://jin66yue-arch.github.io/my-homepage/
- **关于我**：https://jin66yue-arch.github.io/my-homepage/about.html
- **作品集**：https://jin66yue-arch.github.io/my-homepage/projects.html
- **灵感记录**：https://jin66yue-arch.github.io/my-homepage/journal.html
- **小工具箱**：https://jin66yue-arch.github.io/my-homepage/app/

## 项目结构

```text
my-homepage/
├── index.html          # 个人主页入口
├── about.html          # 个人介绍页面
├── projects.html       # 作品集页面
├── journal.html        # 灵感记录页面
├── app/                # 独立的小工具箱（PWA）
│   ├── index.html      # 小工具箱界面与功能
│   ├── manifest.json   # 安装信息与应用显示设置
│   ├── sw.js           # 离线缓存与 Service Worker
│   ├── icons/          # 应用图标
│   └── README.md       # 小工具箱文件说明
├── .nojekyll           # 告知 GitHub Pages 不使用 Jekyll 处理
└── README.md           # 本说明文件
```

## 维护约定

1. 根目录的 `index.html` 是个人主页入口，请不要和 `app/index.html` 混淆。
2. 小工具箱放在 `app/` 中，保留它的相对路径、`manifest.json` 和 `sw.js` 配置。
3. 暂时不要随意移动或重命名 HTML 文件，否则页面导航、应用安装或离线缓存可能失效。
4. 新增页面前，先决定它属于个人网站还是小工具箱，再放进对应位置。
5. 修改后检查相关页面链接，并在手机浏览器中打开确认。

## 技术说明

- 静态 HTML、CSS 与 JavaScript
- GitHub Pages 托管
- 小工具箱使用浏览器本地存储保存任务、笔记和倒计时；清除网站数据或更换设备可能导致数据丢失
