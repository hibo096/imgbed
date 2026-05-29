# imgbed

个人图床，配合 jsDelivr CDN 使用。

## 取图链接

```
https://cdn.jsdelivr.net/gh/hibo096/imgbed@main/<路径>
```

例：`BCI/figure-1.png` →
`https://cdn.jsdelivr.net/gh/hibo096/imgbed@main/BCI/figure-1.png`

## 上传方式

- 直接 `git add / commit / push`，或
- 用 PicGo 客户端拖拽上传（后端选 GitHub，仓库 `hibo096/imgbed`，分支 `main`，自定义域名填 `https://cdn.jsdelivr.net/gh/hibo096/imgbed`）

## 说明

- 仓库公开仅为让 jsDelivr 免鉴权出图，只存图片，不放任何隐私内容。
- 同名文件更新后 jsDelivr 有缓存，新增文件即时生效。
