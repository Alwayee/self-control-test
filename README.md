# 自控力测试

一个无需构建步骤的单页静态网站，使用原生 HTML、CSS 和 JavaScript 编写。

## 本地预览

在项目目录运行：

```bash
python3 -m http.server 8000
```

然后访问 <http://localhost:8000>。

## 部署

将仓库推送到 GitHub 后，在 Vercel 中导入该仓库即可。Framework Preset 选择 `Other`，Root Directory 保持仓库根目录，Build Command 留空，Output Directory 留空。
