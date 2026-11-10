# Yicen Liu 学术博客

本网站基于 [Chirpy Jekyll Theme](https://github.com/cotes2020/jekyll-theme-chirpy)，包含个人简介、博客、出版物、研究项目和档案。

## 本地预览

需要安装 Ruby 和 Bundler。在项目目录运行：

```bash
bundle install
bundle exec jekyll serve
```

然后打开 `http://127.0.0.1:4000/`。不要直接双击 `index.html`；Jekyll 需要先处理页面模板和样式。

## GitHub Pages

推送到 `main` 后，`.github/workflows/pages-deploy.yml` 会构建并部署网站。仓库的 Pages 设置需要使用 GitHub Actions。

## 内容位置

- `_tabs/`：个人简介、博客、出版物和项目页面
- `_posts/`：博客文章
- `assets/img/`：图片资源
- `_config.yml`：网站标题、域名和个人信息
