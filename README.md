# 王唤卿的博客

基于 GitHub Pages 的个人博客，纯 HTML + CSS，无需构建工具，推送即可访问。

访问地址：[whq410727.github.io](https://whq410727.github.io)

## 目录结构

```
.
├── index.html          # 首页（文章列表）
├── about.html          # 关于页面
├── style.css           # 全局样式
├── posts/              # 文章目录
│   ├── hello-world.html
│   ├── pandas-cheatsheet.html
│   └── logistic-regression.html
└── README.md
```

## 如何写新文章

1. 在 `posts/` 目录下新建一个 `.html` 文件，文件名用英文，如 `my-first-post.html`
2. 复制任意一篇现有文章的 HTML 结构作为模板
3. 修改标题、日期、分类和正文内容
4. 回到 `index.html`，在 `<div class="post-list">` 中添加一张新的文章卡片，链接指向新文件

## 本地预览

直接用浏览器打开 `index.html` 即可预览，无需任何服务器。

## 部署

将所有文件推送到 GitHub 仓库的 `main` 分支根目录，在仓库 **Settings → Pages** 中选择 `main` 分支即可。
