# 黄平洋个人学术主页（Academic Pages 版本）

这是基于 [Academic Pages](https://github.com/academicpages/academicpages.github.io) 模板制作的个人学术主页版本，用于展示教育背景、科研经历、论文成果、竞赛荣誉、综合素质和联系方式。

> 说明：本目录是独立的新模板版本，不会覆盖原来的 Hugo 主页。原 Hugo 主页仍保留在 `F:\桌面\myself\homepage`。

## 本地位置

```powershell
F:\桌面\myself\homepage-academic-pages
```

## 主要内容位置

- 站点配置：`_config.yml`
- 导航栏：`_data/navigation.yml`
- 页面内容：`_pages/`
- 头像：`images/profile.jpg`
- 科研图片：`images/research/`
- 简历 PDF：`files/cv.pdf`
- 自定义样式：`_sass/_academic_custom.scss`

## 本地预览

Academic Pages 是 Jekyll 模板，预览方式通常为：

```powershell
bundle install
bundle exec jekyll serve
```

如果本机没有 Ruby / Bundler，可以直接使用 GitHub Pages 自动构建，或后续安装 Ruby 环境后再本地预览。

## 部署提示

请不要直接推送到当前已经部署 Hugo 主页的 `huangpingyang04-lgtm.github.io` 仓库，否则会覆盖原主页。建议：

1. 新建一个仓库，例如 `homepage-academic-pages`。
2. 将本目录内容推送到新仓库。
3. 在 GitHub Pages 设置中选择从 GitHub Actions 或默认 Pages 分支部署。
4. 如果使用项目页部署，需在 `_config.yml` 中把 `url` 和 `baseurl` 调整为对应地址。
