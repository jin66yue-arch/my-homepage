# Jinyue · Personal Website

这是 Jinyue 的个人网站仓库，使用 GitHub Pages 发布。

## 在线页面

- **个人主页**：https://jin66yue-arch.github.io/my-homepage/
- **关于我**：https://jin66yue-arch.github.io/my-homepage/about.html
- **作品集**：https://jin66yue-arch.github.io/my-homepage/projects.html
- **灵感记录**：https://jin66yue-arch.github.io/my-homepage/journal.html
- **独立小工具箱仓库**：https://github.com/jin66yue-arch/toolbox

## 项目结构

```text
my-homepage/
├── index.html
├── about.html
├── projects.html
├── journal.html
├── app/                # 旧入口：跳转到独立小工具箱
│   ├── index.html
│   └── sw.js
├── .nojekyll
└── README.md
```

## 项目划分

- `my-homepage`：个人主页、个人介绍、作品集和灵感记录。
- `toolbox`：独立维护 iPhone 小工具箱（PWA），包括待办、倒计时、随手记、文本工具、应用图标和离线缓存。
- 旧地址 `/my-homepage/app/` 保留跳转页，避免之前保存的入口失效。新工具箱需要在 toolbox 仓库启用 GitHub Pages 后才能通过独立网址访问。

## 技术说明

- 静态 HTML、CSS 与 JavaScript
- GitHub Pages 托管
- 小工具箱的数据保存在当前浏览器本地；清除网站数据或更换设备可能导致数据丢失。
