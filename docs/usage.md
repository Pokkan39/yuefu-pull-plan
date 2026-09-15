# 独立站点使用说明

本站是独立静态页面，不依赖原 zzz-home 仓库，无需构建。

## 静态预览与发布

在本站根目录运行 `python -m http.server 8000`，在浏览器打开本机 8000 端口的首页即可预览。

发布到 GitHub Pages 时，将本站作为独立仓库内容发布，站点入口为仓库根目录 `index.html`，发布目录选择仓库根目录，并保留 `.nojekyll`。远程仓库可使用 `Pokkan39/yuefu-pull-plan`；本说明不代表已完成线上部署。

## 文件依赖

入口 `index.html` 依赖同目录 `pull-plan.css`、`pull-plan.js`，以及 `assets/pull-plan/` 内的 25 个 PNG 和 `assets/fonts/zzz/zzz-en.ttf`、`zzz-zh.ttf`。保持这些相对路径不变。

角色图片素材为官方立绘，不是 AI 生成。若手机浏览器剪贴板权限受限，页面会提示手动复制；不保证所有设备均可自动复制。
