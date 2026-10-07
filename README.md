# 生活岛 · 集成式生活工作台

一个零外部依赖的单文件静态网页，可直接部署到 GitHub Pages。

## 预览
打开 `index.html` 即可使用。

## 部署到 GitHub Pages
1. 在 GitHub 新建一个仓库（如 `life-desk`）。
2. 将本目录推送到该仓库：
   ```bash
   git remote set-url origin https://github.com/<你的用户名>/life-desk.git
   git push -u origin master
   ```
3. 在仓库 Settings → Pages 中，将 Source 设置为 `Deploy from a branch`，Branch 选择 `master` / root，保存。
4. 访问 `https://<你的用户名>.github.io/life-desk/`
