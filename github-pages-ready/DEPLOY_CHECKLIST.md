# GitHub 发布检查清单

## 1. 上传前检查

- [ ] 仓库根目录存在 `index.html`
- [ ] 仓库根目录存在 `.nojekyll`
- [ ] 不要只上传 `edited.html`
- [ ] 本地双击 `index.html` 可正常打开
- [ ] 页面标题、封面、联系方式或署名已确认

## 2. 推荐仓库结构

```text
/
├── index.html
├── .nojekyll
├── README.md
└── DEPLOY_CHECKLIST.md
```

## 3. GitHub Pages 设置

在 GitHub 仓库中依次进入：

```text
Settings → Pages → Build and deployment
```

推荐配置：

```text
Source: Deploy from a branch
Branch: main
Folder: /root
```

## 4. 发布后检查

- [ ] 打开 GitHub Pages 地址后能看到页面封面
- [ ] 手机端可正常浏览
- [ ] 滚动页面时没有明显空白、错位、图片丢失
- [ ] 分享链接不需要登录 GitHub 即可访问

## 5. 常见问题

### 打开后 404

通常是因为文件没有命名为 `index.html`，或 Pages 没有选择 `/root`。

### 页面样式丢失

当前页面样式写在 `index.html` 内，一般不会丢失。若后续拆分 CSS/JS，需同步上传资源文件夹。

### 图片不显示

当前图片为 base64 内嵌图片，一般不会丢失。若后续改为外链图片，需确认图片链接可公开访问。
