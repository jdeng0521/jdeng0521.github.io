# 个人主页

双击 `index.html` 即可在浏览器预览。正文和样式都在这一个文件里，无需安装依赖或运行构建。

## 修改内容

- 用文本编辑器打开 `index.html`，可以直接修改简介、经历和教育背景。新增或删除研究条目时，留意链接和对应的锚点。
- 若要换成照片，可将图片放进 `images/`，把 `figure.portrait` 里的 SVG 换成带替代文字的 `<img src="./images/avatar.jpg" alt="Wenbo Deng">`，再删除 figure 上的 `aria-hidden`。上传时保留图片目录结构。
- 更新页面标题 `<title>` 和描述 `<meta name="description">`，保存后刷新浏览器检查文字、链接和图片。

## 发布到 GitHub Pages

1. 想使用 `https://<用户名>.github.io/`，就在自己的账号下创建 `<用户名>.github.io` 仓库，名称使用小写。GitHub Free 需要使用公开仓库。
2. 将 `index.html`、`.nojekyll` 和用到的图片上传到 `main` 分支的仓库根目录。使用已有仓库时，也可以把这些文件放进 `main` 分支的 `docs/` 目录。普通仓库默认网址为 `https://<用户名>.github.io/<仓库名>/`。
3. 在仓库的 **Settings → Pages → Build and deployment** 下选择 **Deploy from a branch**。选中 `main` 和实际使用的目录 **/(root)** 或 **/docs**，然后保存。部署完成后，在 **Settings → Pages** 点击 **Visit site**。

[创建 GitHub Pages 网站](https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site) · [配置发布来源](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site)
