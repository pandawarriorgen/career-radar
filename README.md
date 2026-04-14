# SIS Career Radar

这是 GitHub Pages 专用静态网站包。

## 需要上传的文件

把这个文件夹里的文件上传到 GitHub 仓库根目录：

- `index.html`
- `styles.css`
- `career.js`
- `.nojekyll`
- `README.md`

不要上传简历 PDF、本地检查报告、Cloudflare 隧道程序、日志文件或压缩包。

## GitHub Pages 发布步骤

1. 登录 GitHub。
2. 点击右上角 `+`，选择 `New repository`。
3. 仓库名建议用 `career-radar`。
4. 选择 `Public`。
5. 创建仓库。
6. 进入仓库后点 `Add file` -> `Upload files`。
7. 上传本文件夹里的 `index.html`、`styles.css`、`career.js`、`.nojekyll`、`README.md`。
8. 点 `Commit changes`。
9. 进入 `Settings` -> `Pages`。
10. 在 `Build and deployment` 里，把 `Source` 设为 `Deploy from a branch`。
11. Branch 选择 `main`，Folder 选择 `/(root)`。
12. 点 `Save`。

通常 1-5 分钟后会生成网址：

`https://你的GitHub用户名.github.io/career-radar/`

如果仓库名改成 `你的GitHub用户名.github.io`，网址会是：

`https://你的GitHub用户名.github.io/`

## 常见问题

- 如果 404，等 1-5 分钟后刷新，或检查 Pages 是否选择了 `main` + `/(root)`。
- 如果页面只有文字没有样式，检查 `styles.css` 是否和 `index.html` 在同一层。
- 如果岗位卡片不显示，检查 `career.js` 是否和 `index.html` 在同一层。
- 如果看不到 `.nojekyll`，这是隐藏文件；可以在 GitHub 网页里用 `Add file` -> `Create new file` 新建一个名为 `.nojekyll` 的空文件。

GitHub 官方文档：

- https://docs.github.com/zh/pages/getting-started-with-github-pages/creating-a-github-pages-site
- https://docs.github.com/zh/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site
