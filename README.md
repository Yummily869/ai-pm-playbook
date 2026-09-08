# AI 产品认知与工作框架

> 总结了 AI 产品工作过程中的几个必要步骤，并将其沉淀为可复用的 skill。

---

## 这里面有什么

### `skills/` — 5 个工作 skill

每个 skill 包含：**适用场景、使用方法、常见坑、空白模板、自检清单**。

| Skill | 解决什么问题 |
|---|---|
| [需求背景](./skills/requirement-background/) | 怎么论证「为什么要做这个 AI 需求」，从市场/公司/用户/竞品四层收窄 |
| [Prompt 撰写](./skills/prompt-writing/SKILL.md) | 输入一句话需求，输出可直接使用的完整 Prompt。覆盖生成类/结构化输出类/对话类三种场景 |
| [模型选型](./skills/model-selection/) | 能力匹配 → 性能时延 → 成本，三个约束按顺序收窄，而不是加权打分 |
| [效果评测](./skills/evaluation/SKILL.md) | 把「好不好看」拆成可判定的维度和子项，建立可对比的评分体系 |
| [灰度放量](./skills/rollout/) | 技术稳定性和产品价值是两道独立的门，每个阶段看什么、卡住时怎么判断 |

### `notes/` — AI 产品认知

[AI 产品认知](./notes/ai-product-thinking.md) — 产品形态分类与留存逻辑差异、AI 产品的三类价值创造方式、从模型能力边界推导产品边界的方法，以及为什么沉淀了这几个 skill。

### `toolkit/` — 可直接使用的代码

[容错 JSON 解析器](./toolkit/robust_json_parser.py)，覆盖工作流节点调用大模型时常见的 11 种输出失败情况。

### `references/` — 模型厂商官方提示词规范

收录 MiniMax H3 与 Seedance 2.0 的官方规范原文，并对比了两者互相冲突的地方（如**时间表达方式**：H3 用绝对秒数，Seedance 禁用秒数必须用镜头序号）。

[查看对比与说明](./references/README.md)

---

## License

[MIT](./LICENSE)
