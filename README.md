# decks

Youngs Group · 网页 PPT 集合。

单 HTML 文件，无构建步骤。模板来源：[guizang-ppt-skill](https://github.com/op7418/guizang-ppt-skill)（电子杂志风 + 瑞士国际主义风）。

## 部署

- **托管**：GitHub Pages（`woodywuwu/decks`）
- **URL**：https://woodywuwu.github.io/decks/
- **触发**：push 到 `main` 分支后自动构建，约 30-60 秒生效

## 新增一份 PPT

1. 在仓库根目录放一份独立 HTML，命名建议短英文 / 拼音
2. 同步在 `index.html` 总入口加一张卡片
3. `git add` → `git commit -m "Add: <标题>"` → `git push origin main`
4. 1 分钟后访问 `https://woodywuwu.github.io/decks/<文件名>.html`

## 当前 PPT

| 文件 | 标题 | 风格 | 场景 |
|---|---|---|---|
| `creative-process.html` | 创意团队前期合作工作进度模板 | 杂志风 | 内部培训 |

## 维护

- 本仓库 **不进 git LFS**，单文件 < 1MB
- 不在仓库内嵌图片（用外链或相对路径）
- commit message 中文即可
