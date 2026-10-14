# 索引卡 · 新标签页 —— 隐私政策页

这个仓库只放一个静态页面：Chrome 扩展「索引卡 · 新标签页」的隐私政策。

- 线上地址：https://mapotato-ma.github.io/newtab-privacy/
- 用途：Chrome 应用商店上架时需要的「隐私政策网址」

扩展本身不收集任何用户数据，详见页面正文。

## 维护方式

**源文件在扩展仓库里**：`Mapotato-Ma/newtab-ext` 的 `privacy.html`。
改完那边复制到这个仓库的 `index.html` 再推，Pages 会自动重建（约 1 分钟）。

```bash
cp /path/to/newtab-ext/privacy.html index.html
git add -A && git commit -m "docs: 隐私政策更新到 x.y.z" && git push
```
