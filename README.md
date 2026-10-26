# bell's Blog

基于 [Hugo](https://gohugo.io/) + [Stack 主题](https://github.com/CaiJimmy/hugo-theme-stack) 的个人博客，部署在 GitHub Pages。

## 写作

新增中文文章：

```bash
hugo new posts/my-post.md
```

新增英文文章，对应文件放 `content/en/posts/my-post.md`。

写完推送到 `main` 分支，GitHub Actions 会自动构建并部署。

## 目录约定

- `content/posts/` 中文文章
- `content/en/posts/` 英文文章
- `i18n/zh.toml` 界面中文翻译

## 本地预览

```bash
hugo server -D
```
