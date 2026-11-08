# know-my-name

BLG vs T1 观赛记录页 —— 记录这场对决的实时比分。

> 起因：凌晨等比赛，随手建了个仓库，于是顺手做成了观赛页。

## 在线预览

开启 GitHub Pages 后访问：`https://qianfang171.github.io/know-my-name/`

## 怎么更新比分

编辑 `index.html`，找到这两行：

```html
<span class="score" id="blg-score">0</span>
<span class="score" id="t1-score">0</span>
```

把 `0` 改成实际比分，然后：

```bash
git add .
git commit -m "比分更新：BLG x - x T1"
git push
```

等一分钟页面自动刷新。

## 技术栈

单文件 `index.html`，纯 HTML + CSS，无依赖、无构建，GitHub Pages 直接托管。
