# AI 产品认知与工作框架

> 记录我在做AI产品过程中的思考，以及从实际工作中总结的方法和框架：其中`notes/` 是对 AI 产品本身的理解，包括产品形态，用户价值和设计取舍。`skills/` 将工作中的常见环节整理成可执行的步骤和工具，用于提高工作效率。内容以我实际参与的产品和工作经验为例，结合公开资料补充思考。后续会持续更新，不断修正。

---

## 这里面有什么

### `skills/` — 3 个工作 skill

| Skill | 解决什么问题 |
|---|---|
| [需求价值论证](./skills/requirement-background/) | 怎么论证「为什么要做这个 AI 需求」，从市场/公司/用户/竞品/商业化五层收窄 |
| [Prompt 撰写](./skills/prompt-writing/SKILL.md) | 填平用户意图语言与模型工程指令之间的鸿沟，输出可直接使用的完整 Prompt |
| [效果评测](./skills/evaluation/SKILL.md) | 把「好不好」拆成可判定的维度和子项，建立可对比的评分体系 |

### `notes/` — AI 产品认知

[AI 产品认知](./notes/ai-product-thinking.md) — 产品形态分类与留存逻辑差异、AI 产品的三类价值创造方式、从模型能力边界推导产品边界的方法，以及为什么沉淀了这几个 skill。

### `references/` — 模型厂商官方提示词规范

收录 MiniMax H3 与 Seedance 2.0 的官方规范原文，并对比了两者互相冲突的地方（如**时间表达方式**：H3 用绝对秒数，Seedance 禁用秒数必须用镜头序号）。

[查看对比与说明](./references/README.md)

---

## License

[MIT](./LICENSE)
