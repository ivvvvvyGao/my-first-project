# 我的个人网站

一个支持中文、手机和电脑的个人网站，使用原生 HTML、CSS 和 JavaScript，无需安装第三方依赖。

## 项目结构

```text
my-first-project/
├── index.html   # 页面内容：首页、关于我、作品展示和页脚
├── styles.css   # 页面样式：颜色、布局、装饰图形和手机适配
├── script.js    # 页面交互：手机菜单、作品筛选、导航状态和年份
└── README.md    # 项目说明与预览指南
```

你可以把 HTML 理解成房子的结构，CSS 理解成装修，JavaScript 则负责按钮等交互。三个文件通过 HTML 中的 `link` 和 `script` 标签连接起来。

## 如何预览

最简单的方法：下载仓库后，双击 `index.html`，用浏览器打开即可。

如果已安装 Python，也可以在项目目录中运行：

```sh
python3 -m http.server 8000
```

Windows 上可以使用 `python -m http.server 8000`。然后在本机浏览器访问 `http://localhost:8000`。按 `Ctrl+C` 停止服务。

在 VS Code 中，也可以安装 Live Server 扩展，右键 `index.html`，选择 **Open with Live Server**。

## 如何修改成自己的网站

1. 在 `index.html` 中替换“我的空间”、个人介绍和作品内容。
2. 两个学习计划是明确标记的未来作品，不代表已完成项目。完成后可替换卡片文字和链接，并修改分类。
3. 在 `styles.css` 顶部的 `:root` 中调整主题颜色；底部的 `@media` 控制不同屏幕的布局。
4. 在 `script.js` 中查看带中文注释的菜单和筛选逻辑。
5. 本项目不使用外部字体、图片或 CDN，页面可以离线浏览。

## 发布到 GitHub Pages

代码推送到 GitHub 后：

1. 打开仓库 **Settings → Pages**。
2. 在 **Build and deployment** 中选择 **Deploy from a branch**。
3. 选择 `main` 分支和 `/ (root)` 目录，然后保存。
4. 等待部署完成，使用 Pages 设置中显示的网站地址访问。

这里只提供发布说明，GitHub Pages 是否启用以仓库设置为准。
