# Materials Manuscript Writing · 材料论文写作

A reusable agent skill for clear, precise, concise writing in materials chemistry and physics.

面向材料化学与物理学论文的写作、翻译、润色、压缩和结构调整。围绕研究目的、已完成的贡献和读者的理解顺序，协调摘要、引言、正文、图注、实验方法、结论与补充材料。

## 写作原则

- **逻辑清楚**：用研究问题连接方法、结果和新增认识；按读者需要安排证据。
- **表述精确**：明确样品、添加量基准、物理量、测试条件和比较对象；保持图文及术语一致。
- **语言凝练**：使用常见动词与准确的专业名词，压缩重复背景、模糊评价和无信息量总结。
- **突出贡献**：直接呈现已完成的工作与依据，把事实核对融入修改过程。
- **章节协调**：让不同部分各自完成任务，并围绕同一主要贡献相互呼应。

正式稿围绕已完成的工作、结果与依据展开。用具体范围、条件和数量控制表述强度；事实核对融入修改过程，不惯例性追加自我否定的结尾、局限段或未来实验清单。

## 包含内容

| 模块 | 内容 |
| --- | --- |
| 摘要与引言 | 高度概括发现，从背景与问题自然引出本文工作 |
| 结果与讨论 | 组织段落、比较与机制解释，让证据支持主要认识 |
| 图与图注 | 协调分图、正文引用、必要条件、符号与统计说明 |
| 方法与精确表达 | 定义样品、百分比、物理量及可复现的操作细节 |
| 结论 | 汇总工作所建立的认识及其意义 |
| 补充材料 | 安排补充结果、方法、图注与主文引用 |
| 数量与比较 | 区分投料、溶液与固体组成，明确物理量、测试状态和归一化基准 |
| 句子与段落 | 用简单动词连接专业名词，压缩重复，以内容自然衔接 |
| 跨章节衔接 | 协调术语、信息分配与叙述节奏 |
| 阅读资料 | 500篇公开论文的题录与写作笔记、38个写作案例、原有70条与新增2355条选段定位记录 |

本次新增300篇均取得正文并完成分章节选段阅读，各有独立写作笔记；其中6篇另作正文专题精读，4份SI读取42个指定页面。新增22个案例与原有16个案例共同支持按任务调用。阅读索引逐篇记录阅读范围、全文版本与来源；引用计数为2026年11月6日的Europe PMC快照。资料以写作笔记和来源索引为主，具体科学结论可通过DOI及开放全文链接回到原文核对。

## 使用

安装或导入目录 [`skills/materials-manuscript-writing`](skills/materials-manuscript-writing)。该目录包含完整的 `SKILL.md`、章节参考文件与界面元数据，可用于支持此类技能格式的代理环境。

```bash
git clone https://github.com/Hua-luo991/materials-manuscript-writing.git
```

将 `skills/materials-manuscript-writing` 放入目标环境的个人技能目录，或通过该环境提供的导入功能安装。普通对话中，也可以提供 `SKILL.md` 及任务所需的参考文件作为写作指导。

示例请求：

> 使用 materials-manuscript-writing 修改这份材料论文。保留科学含义和已确认数据，重点改善逻辑、准确性与简洁性，并协调正文和图注。先给出可直接使用的修改稿。

> 使用 materials-manuscript-writing 压缩摘要，并检查引言末段、主要结果和结论是否围绕同一贡献展开。

> 使用 materials-manuscript-writing 整理补充材料，补齐图注中的样品定义、测试条件及主文引用。

## 文件入口

- [`SKILL.md`](skills/materials-manuscript-writing/SKILL.md)：核心流程和按任务加载的模块导航。
- [`references/`](skills/materials-manuscript-writing/references)：各章节规范、改写示例和文献阅读资料。
- [`literature-index.csv`](skills/materials-manuscript-writing/references/literature-index.csv)：500篇论文的检索入口。
- [`literature-cases.md`](skills/materials-manuscript-writing/references/literature-cases.md)：16个写作案例。
- [`close-reading-cases.md`](skills/materials-manuscript-writing/references/close-reading-cases.md)：新增22个材料化学、物理与SI案例。
- [`reading-protocol.md`](skills/materials-manuscript-writing/references/reading-protocol.md)：新增300篇的阅读范围、期刊分布、稿本与SI页序。
- [`quantity-comparisons.md`](skills/materials-manuscript-writing/references/quantity-comparisons.md)：数量定义、样品状态与性能比较。
- [`sentence-craft.md`](skills/materials-manuscript-writing/references/sentence-craft.md)：句子压缩与自然衔接。
- [`sources.md`](skills/materials-manuscript-writing/references/sources.md)：来源、阅读范围与复核方式。

## 改进

欢迎提供具体的原句、修改目标与使用反馈。修改时应优先保留准确的科学含义，使用具体的对象、条件和数据控制表述强度，并使最终文字适合直接用于正式稿件。
