# 刘正春个人 GitHub Pages

这是一个零构建的个人介绍静态站点，用于展示 AI 应用工程师 / AI Agent 开发工程师方向的个人定位、项目经历与联系方式。

## 目录结构

```text
docs/
  index.html      # GitHub Pages 首页
  favicon.svg     # 网站图标
.github/workflows/
  deploy-pages.yml
```

## 本地预览

```bash
cd docs
python -m http.server 9000
```

访问 `http://localhost:9000`。

## GitHub Pages 部署

1. 将本仓库推送到 GitHub。
2. 进入仓库 `Settings → Pages`。
3. `Source` 选择 `GitHub Actions`。
4. 进入 `Actions`，手动运行 `Deploy GitHub Pages`，或直接 push 到 `main` 触发部署。

部署成功后访问：

```text
https://<github-username>.github.io/<repo-name>/
```

