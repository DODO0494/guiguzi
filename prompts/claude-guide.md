# Claude 使用指南

## 快速开始

### 方式一：Project System Prompt（推荐）

1. 打开 Claude → Projects → Create Project
2. 在 System Prompt 中粘贴 `prompts/universal-prompt.md` 的 System Prompt 内容
3. 将 `modules/` 目录下的模块文件上传到 Project Knowledge
4. 开始对话

### 方式二：直接对话

在对话开头粘贴 System Prompt 内容，然后提出你的问题。

## Claude 特有优势

Claude 的长上下文窗口（200K tokens）意味着你可以把多个模块文件直接放进对话上下文中，获得更深度、更精确的分析。

**推荐做法**：
1. 先粘贴 `prompts/universal-prompt.md` 的 System Prompt
2. 再粘贴与你问题最相关的 1-2 个模块文件全文（从 `modules/` 目录中选取）
3. 提出你的具体问题

这样 Claude 既有全局路由能力，又有具体框架的完整执行细节。

## 模块选择指南

| 你的问题 | 建议附带的模块文件 |
|---------|-----------------|
| 谈判/沟通 | s01-bai-he-shu.md + s02-fan-ying-shu.md |
| 情报/尽调 | s07-chuai-mo-shu.md |
| 关系经营 | s03-nei-jian-shu.md + s05-fei-qian-shu.md |
| 方案设计 | s09-mou-shu.md + s04-di-xi-shu.md |
| 决策选择 | s10-jue-shu.md |
| 职场/组织 | s04-di-xi-shu.md + s06-wu-he-shu.md |
