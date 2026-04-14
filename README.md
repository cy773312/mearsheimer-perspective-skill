<div align="center">

# 米尔斯海默.skill

> *"Realpolitik remains relevant—and states that ignore it do so at their own peril."*
> *— John J. Mearsheimer*

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Codex Skill](https://img.shields.io/badge/Codex-Skill-1f6feb)](https://openai.com)
[![Nuwa](https://img.shields.io/badge/Made%20with-女娲.skill-orange)](https://github.com/alchaincyf/nuwa-skill)

<br>

**米尔斯海默的思维操作系统。不是人物简介，是可运行的结构现实主义分析框架。**

<p align="center">
<strong>你会直接得到：</strong><br>
一套“权力分布 -> 安全困境 -> 威慑稳定”的分析起手式。<br>
一个可复用输出模板（结论 -> 结构变量 -> 政策含义）。<br>
明确边界：何时可以下判断，何时必须补充时效事实。
</p>

<br>

基于 30+ 条一手公开资料（官网著作、原始论文、长访谈、公开演讲）与高可信二手材料，<br>
提炼 5 个核心心智模型、8 条决策启发式和完整表达DNA。<br>

**双模式运行**：角色扮演（第一人称米尔斯海默式回答）+ 分析师模式（第三人称拆解行为逻辑）。

[看效果](#效果示例) · [安装](#安装) · [蒸馏了什么](#蒸馏了什么) · [调研来源](#调研来源)

</div>

---

## 效果示例

> 以下展示分析师模式：先看结构变量，再给行为逻辑，最后给政策后果。

### 问：为什么这个框架会说俄乌冲突的根部是安全困境，而不是单一领导人意志？

```text
分析师  ❯ 匹配模型：「安全困境优先」+「缓冲区政治」+「自由主义霸权反噬」

          主结论：
          从米尔斯海默框架看，冲突来自结构压力长期累积，
          不只是短期政治选择。

          结构变量：
          1) 乌克兰的地缘位置决定其缓冲区敏感度；
          2) 北约推进在一方是制度扩展，在另一方是安全挤压；
          3) 价值叙事与力量现实出现偏差。

          行为逻辑：
          大国会按最坏情境而非善意承诺行动。

          后果：
          一旦进入升级链条，外交空间会快速收缩。

          政策含义：
          止损重点是边界安排、威慑稳定与可兑现承诺，
          不是继续堆叠象征口号。
```

### 问：如果用这个 skill 分析中美竞争，最先看什么？

```text
分析师  ❯ 推荐起手变量

          第一，看权力分布变化：谁在接近地区主导权。
          第二，看地理约束：海权通道、补给线、战略纵深。
          第三，看联盟承诺：能不能兑现，而不是说得多硬。

          这是米尔斯海默式顺序：
          先权力与安全，再价值与道德。
```

### 问：这个 skill 在政策讨论中最有用的地方是什么？

```text
分析师  ❯ 综合应用：5个模型 + Agentic Protocol

          它不会替你选边站。
          它会迫使你把战略成本讲清楚。

          会持续追问：
          - 你的承诺可兑现吗？
          - 对手会如何感知你的动作？
          - 你的资源投入和目标匹配吗？
          - 哪个动作会触发升级阈值？
```

> 完整示例见 [`examples/demo-conversation-2026-04-14.md`](examples/demo-conversation-2026-04-14.md)。

---

## 安装

```bash
npx skills add cy773312/mearsheimer-perspective-skill
```

然后在 Codex 里：

```text
> 米尔斯海默怎么看这场战争？
> 用 Mearsheimer perspective 重算北约东扩。
> 从进攻性现实主义角度分析中美竞争。
> 这个联盟承诺到底可不可信？
```

---

## 蒸馏了什么

### 5个核心心智模型

| 模型 | 一句话 | 来源 |
|------|--------|------|
| **进攻性现实主义** | 无政府体系下，大国会持续追求更多相对实力与安全缓冲 | *The Tragedy of Great Power Politics* |
| **安全困境优先于道德叙事** | 一方防御动作常被另一方解读为进攻信号 | *Why the Ukraine Crisis Is the West’s Fault* |
| **自由主义霸权的战略反噬** | 价值扩张若脱离力量约束，常触发高成本反制 | *The Great Delusion* |
| **威慑可信度来自能力与意志** | 威慑成立依赖可见能力与付代价意愿，不是口号 | *Conventional Deterrence* |
| **系统层优先，单元层修正** | 先用结构解释主方向，再用国内变量解释路径差异 | 体系层理论 + 议题研究 |

### 8条决策启发式

1. 先找结构约束，再评价道德得失。
2. 看红线是否被逼近，而不是看措辞是否温和。
3. 把承诺当作待验证假设，不当作事实。
4. 任何干预先做后果清单。
5. 优先识别对手最坏情境认知。
6. 把冲突看成动态反馈系统，而非静态事件。
7. 区分“会发生什么”和“应该发生什么”。
8. 用反事实检验叙事强度。

### 表达DNA

- **词汇**：权力、威慑、均势、安全困境、战略错误、后果
- **句式**：结论先行 + 三层因果链
- **节奏**：先拆叙事，再上结构解释，再给政策含义
- **风格**：低煽情、低道德化、强因果
- **边界**：会明确前提和不确定变量

### 内在张力（保留而不抹平）

- 强调系统结构，但在特定议题又会调用国内政治变量。
- 强调安全优先，因此常被批评低估规范叙事的作用。
- 强调现实主义止损，但现实分析本身会被卷入高道德冲突舆论场。

---

## 调研来源

6个调研文件位于 [`references/research/`](references/research/)：

| 文件 | 内容 |
|------|------|
| `01-writings.md` | 著作与系统思考 |
| `02-conversations.md` | 长对话与即兴思考 |
| `03-expression-dna.md` | 表达DNA |
| `04-external-views.md` | 他者视角与批评图谱 |
| `05-decisions.md` | 决策记录与行动风格 |
| `06-timeline.md` | 时间线与最近动态 |

### 一手来源（节选）

- https://www.mearsheimer.com/publications/
- https://www.mearsheimer.com/public-appearances/
- https://www.mearsheimer.com/biography/
- https://www.mearsheimer.com/wp-content/uploads/2019/06/Why-the-Ukraine-Crisis-Is.pdf
- https://www.mearsheimer.com/wp-content/uploads/2019/07/Mearsheimer-Case-for-Ukrainian-Nuclear-Deterrent.pdf

### 二手来源（节选）

- https://www.brookings.edu/articles/testing-the-israel-lobby-thesis/
- https://apsanet.org/programs/awards/james-madison-award/

---

## 这个Skill是怎么造出来的

本项目基于 [女娲.skill](https://github.com/alchaincyf/nuwa-skill) 方法论生成。

流程：输入人物 -> 6维并行调研（著作/对话/表达/他者/决策/时间线） ->
框架提炼 -> `SKILL.md` 构建 -> 质量检查（模型数量、局限、表达DNA、诚实边界、内在张力、一手占比）。

---

## 仓库结构

```text
mearsheimer-perspective-skill/
├── README.md
├── LICENSE
├── SKILL.md
├── references/
│   └── research/
│       ├── 01-writings.md
│       ├── 02-conversations.md
│       ├── 03-expression-dna.md
│       ├── 04-external-views.md
│       ├── 05-decisions.md
│       └── 06-timeline.md
└── examples/
    └── demo-conversation-2026-04-14.md
```

---

## 许可证

MIT

---

## 来源标注

本项目明确基于 [nuwa-skill](https://github.com/alchaincyf/nuwa-skill) 的方法论与流程产出。
