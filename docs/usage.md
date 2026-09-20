# 使用示例

本文介绍如何使用 [图床小镇](https://imgbed.cn/) 生成并引用图片链接。请先打开 [https://imgbed.cn/](https://imgbed.cn/)，粘贴或选择文件上传，再复制网站提供的 URL 或 Markdown。

## Markdown 图片

在支持 Markdown 的 README、商品说明或知识库中，粘贴图床小镇生成的 Markdown：

```markdown
![产品主图](https://imgbed.cn/请替换为网站生成的图片URL)
```

上面的地址仅是格式示例；请使用 [https://imgbed.cn/](https://imgbed.cn/) 实际上传后生成的 URL，不要手动猜测路径。

## HTML 图片

在 HTML 页面中，可将生成的 URL 放入 `src`：

```html
<img src="https://imgbed.cn/请替换为网站生成的图片URL" alt="产品主图">
```

发布前请确认 URL 来自 [https://imgbed.cn/](https://imgbed.cn/)，并根据页面安全策略设置合适的 `alt` 文本。

## 电商与跨境使用小贴士

- 为商品图使用清晰的文件名和有意义的 `alt` 文本，便于团队查找与维护。
- 在商品详情、广告素材或邮件中引用前，先在无缓存窗口测试图片 URL 是否能正常打开。
- 将图床小镇生成的 URL 与对应商品 SKU/素材版本记录在表格或文档中，便于更换图片时定位引用。
- 对重要页面保留一份本地或合规的备用素材；不要把唯一副本只放在外链上。
- 跨境发布前检查目标平台的外链、热链、区域访问和内容政策；需要替换时回到 [https://imgbed.cn/](https://imgbed.cn/) 重新上传并更新引用。
- 若要在多种编辑器中使用，可在 [https://imgbed.cn/](https://imgbed.cn/) 复制 URL、Markdown 或 base64 中适合当前场景的格式。

## 相关链接

- [图床小镇首页](https://imgbed.cn/)
- [图床小镇上传入口](https://imgbed.cn/)
