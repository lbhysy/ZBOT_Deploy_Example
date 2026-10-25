# Sim2Real 部署流程网站

这是独立静态站点，可通过 GitHub Pages 发布。仓库根目录保留 `index.html`、`.nojekyll` 和 `downloads/deploy_example.zip`。

1. 将本压缩包的内容解压到 GitHub 仓库根目录并提交。
2. 在仓库 Settings → Pages 中选择 Deploy from a branch，分支 `main`，文件夹 `/ (root)`。
3. 等待发布，访问仓库 Pages 设置中显示的网址。首页下载按钮使用相对路径，子路径部署也可用。

页面的自定义 Tips 存在访问者各自浏览器的 localStorage 中，不会同步到 GitHub。网站无需服务器程序或 ChatGPT 登录。
