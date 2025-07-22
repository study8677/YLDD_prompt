
# Prompt Encyclopedia

Welcome to the Prompt Encyclopedia! This repository is a collection of prompts for various AI models and tasks.

## Structure

Prompts are organized by language (English and Chinese) and then by category.

- `prompts/en/`: English prompts
- `prompts/zh/`: Chinese prompts


## Contributing

Contributions are welcome! Please see the `README_zh.md` for more details if you are a Chinese speaker, or open an issue to discuss potential additions if you are an English speaker.

# 永乐大典 Prompt

永乐大典 Prompt 百科致力于系统化收集、整理与分享 **大语言模型（LLM）** 及多模态模型的高质量 Prompt。无论是科研、写作、教学，还是产品开发，您都能在此找到即插即用的高效提示词，并快速了解它们背后的设计思路与最佳实践。

## 什么是优秀的 Prompt

优秀 Prompt 通常具备以下七大特征：

1. **目标单一、清晰** — 一句话即可说明任务；
2. **上下文充分** — 提供完成任务所必需的背景与受众信息；
3. **输出格式可验证** — 定义明确的结构或数据格式；
4. **约束具体可执行** — 字数、风格、禁用项等要求量化；
5. **示例 / Few‑shot 引导** — 通过正反示例降低歧义；
6. **流程可追踪** — 对复杂任务支持分步确认；
7. **可复用、易维护** — 模块化、命名规范，方便迭代。

下面给出一份经过实战验证的模板，可直接复制并按需填充。

---

### 优秀 Prompt 模板（中文）

> 本模板遵循 **11 分评估体系**，涵盖角色设定、任务目标、上下文、约束、示例与交互流程六大要素。直接复制后按需填写下划线部分即可。

---

## 1. 角色设定

```text
你是一名 ____ （如：领域专家 / 产品经理 / 讲师）
```

## 2. 任务目标

```text
请帮我 ____ ，并以 ____ 格式输出结果。
```

## 3. 背景上下文

| 项目       | 说明（示例） |
| -------- | ------ |
| **受众**   | 研究生    |
| **语气**   | 正式、精炼  |
| **参考资料** | 见附录 A  |

## 4. 约束与要求

1. **字数**：全文 ≤ **1 500** 字
2. **结构**：使用 **有序列表** 分条说明
3. **示例**：每条说明后附 **1** 个具体示例
4. **禁止** 直接引用未提供的外部内容

## 5. 示例（Few‑shot）

<details>
<summary>点击展开</summary>

### 用户输入

```text
...
```

### 期望输出

```markdown
...
```

</details>

## 6. 交互流程

1. **Step 1**：先返回 **20–30 字** 的思路概要供确认
2. **Step 2**：经确认后再输出完整答案

---

### 快速自检清单

* [ ] 任务是否一句话说清？
* [ ] 必要背景是否完整？
* [ ] 是否包含量化的格式/长度/风格约束？
* [ ] 是否提供示例或反例？
* [ ] 对复杂任务是否拆分步骤？
* [ ] Prompt 是否简洁、易维护？

> **提示**：编写完 Prompt 后，将“好的”“详细的”之类模糊形容词替换为 **可度量** 描述，并删除“等”字；如仍有歧义，可增加示例或补充细化约束。

