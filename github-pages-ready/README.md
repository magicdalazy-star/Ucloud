# 优链云食材配送项目全链条管家通用提案

这是一个可直接通过 GitHub Pages 发布的静态 HTML 提案页。

## 文件说明

- `index.html`：网页主文件，GitHub Pages 会默认打开这个文件。
- `.nojekyll`：关闭 Jekyll 处理，避免静态资源或特殊文件名被忽略。
- `DEPLOY_CHECKLIST.md`：发布前检查清单与操作步骤。

## GitHub Pages 发布步骤

1. 新建一个 GitHub 仓库，例如 `ycloud-proposal`。
2. 将本文件夹内的全部文件上传到仓库根目录。
3. 确认仓库根目录存在 `index.html`。
4. 打开仓库 `Settings`。
5. 进入 `Pages`。
6. 在 `Build and deployment` 中选择：
   - Source: `Deploy from a branch`
   - Branch: `main`
   - Folder: `/root`
7. 保存后等待 1-3 分钟。
8. GitHub 会生成访问地址，通常格式为：

```text
https://你的用户名.github.io/仓库名/
```

## 注意事项

- 不要把 `index.html` 改回 `edited.html`，否则 GitHub Pages 默认首页可能无法打开。
- 当前页面为单文件自包含 HTML，图片已内嵌在文件中，无需额外上传 `assets/` 或 `images/`。
- 如需绑定自定义域名，可在 GitHub Pages 设置中配置 Custom domain。
