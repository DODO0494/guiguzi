# ChatGPT 使用指南

## 快速开始

### 方式一：Custom Instructions（推荐）

1. 打开 ChatGPT → Settings → Custom Instructions
2. 将 `prompts/universal-prompt.md` 中 "## System Prompt" 下的内容复制到第二个框（"How would you like ChatGPT to respond?"）
3. 保存，开始对话

### 方式二：创建 GPT

1. 打开 ChatGPT → Explore → Create a GPT
2. 在 Configure → Instructions 中粘贴 `prompts/universal-prompt.md` 的 System Prompt 内容
3. 上传 `modules/` 目录下的模块文件作为 Knowledge Base
4. 发布为你的私人 GPT

### 方式三：对话中直接使用

在对话开头粘贴 System Prompt 内容，然后提出你的问题。

## 使用技巧

- **明确场景**：描述你的具体处境，而不是问抽象问题。"我的合伙人嘴上说支持但总拖延"比"怎么处理合伙人不支持"更好
- **要求分步**：如果回答太笼统，追问"给我具体的操作步骤"
- **多框架组合**：复杂问题可以主动要求"用揣摩术和谋术一起分析"

## 示例对话

```
用户：我下周要见一个潜在投资人，他之前投了我竞品，我该怎么准备？

AI：框架匹配 → s07 揣摩术（情报收集）+ s03 内揵术（关系绑定）

分析：
1. 量权：这个投资人投了你竞品，说明他看好这个赛道。他投竞品的原因、金额、阶段，都是公开可查的...
2. 揣情：他愿意见你，说明他对竞品不是完全满意，或者想更了解赛道...

执行步骤：
Step 1: 量权清单 — 查清他过去12个月的投资记录、偏好领域、典型deal size...
Step 2: 揣情 — 在对话中用"反应术"的沉默和反问探测他对竞品的真实评价...
...
```
