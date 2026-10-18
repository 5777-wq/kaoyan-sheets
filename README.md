# 考研总站 · 总目录

四个复习站的统一入口：材料力学 / 数学公式 / 英语作文 / 智能批改。
线上地址：<https://kaoyan-sheets.pages.dev>

## 结构

单文件站点，无构建、无依赖：

- `index.html` — 页面全部内容（含倒计时脚本）

## 部署

```bash
npx wrangler pages deploy hub --project-name=kaoyan-sheets
```

## 旗下站点

| 站点 | 地址 | 仓库 |
|---|---|---|
| 材料力学 · 复习手册 | <https://mm802-review.pages.dev> | — |
| 考研数学 · 公式看板 | <https://math-formula-board.pages.dev> | — |
| 英语作文 · 模板手册 | <https://kaoyan-essay.pages.dev> | [5777-wq/kaoyan-essay](https://github.com/5777-wq/kaoyan-essay)（私有） |
| DuoGrader · 作文批改 | <https://duograder.pages.dev> | [5777-wq/duograder](https://github.com/5777-wq/duograder) |
