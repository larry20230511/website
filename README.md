# Larry's personal website

一个使用原生 HTML 和 CSS 构建的个人主页，可直接通过 GitHub Pages 发布。

## 本地预览

直接在浏览器打开 `index.html`，或在仓库根目录运行：

```sh
python3 -m http.server 8000
```

然后访问 <http://localhost:8000>。

## 发布到 GitHub Pages

1. 打开仓库的 **Settings → Pages**。
2. 在 **Build and deployment** 中选择 **Deploy from a branch**。
3. 选择 `main` 分支和 `/(root)` 目录并保存。

GitHub Pages 会从根目录的 `index.html` 发布站点。首次发布完成后，可在 Pages 设置中查看访问地址。

主页内容位于 `index.html`，布局与响应式样式位于 `styles.css`。替换示例文案、链接和图片即可继续完善个人资料。
