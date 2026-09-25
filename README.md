# MY

KYOU 的个人作品网页。页面提供日文、英文、中文内容，GitHub Pages 自动发布 `main` 分支的构建结果。

## 本地构建

需要 Node.js 22。运行 `npm install`、`npm run build`，然后用静态文件服务器打开 `dist/index.html`。站点的入口、脚本、样式源文件分别是 `index.html`、`assets/site.js` 和 `src/styles.css`；`images/` 来自原仓库 `kyoushingi-lab/MYMYMY`。

## 发布

推送到 `main` 后，GitHub Actions 会构建 Tailwind 静态 CSS，并把 `dist/` 发布到 GitHub Pages。仓库的 Pages 来源须设为 **GitHub Actions**。

作品资料卡片保留原来的密码提示。密码和链接写在公开的前端代码中，因此这个提示不提供访问控制；如需限制资料访问，应设置资料本身的共享权限。
