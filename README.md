# bell's Blog

基于 Hugo + PaperMod 主题的个人博客，部署在 GitHub Pages。

## 新增文章

```bash
hugo new posts/my-post.md
```

写完推送到 `main` 分支，GitHub Actions 会自动构建并部署。

## 目录约定

- `content/posts/` - 文章目录
- `content/about/` - 关于页面

## 本地预览

```bash
hugo server -D
```
