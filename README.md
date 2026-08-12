# 鬼谷子 AI 谋略系统 | Guiguzi AI Strategy System

> 将《鬼谷子》十二篇智慧提取为 11 套可执行的现代谋略框架，适配所有主流 AI 工具。
>
> Extracting 11 actionable strategy frameworks from the 2,300-year-old classic *Guiguzi*, adapted for all major AI tools.

[![License: CC BY-NC-SA 4.0](https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc-sa/4.0/)
[![Version](https://img.shields.io/badge/version-1.0.0-blue.svg)](https://github.com/DODO0494/guiguzi)
[![Language](https://img.shields.io/badge/language-中文-red.svg)]()
[![AI Ready](https://img.shields.io/badge/AI-ChatGPT%20%7C%20Claude%20%7C%20WorkBuddy-green.svg)]()

---

## 这是什么 | What is this

**中文：**

《鬼谷子》是中国古代谋略学的巅峰之作，相传为战国纵横家鬼谷子（王诩）所著。全书十二篇，从沟通技巧到情报工程，从关系经营到策略设计和决策方法，构成一套完整的"看透人 → 说对话 → 做对事"操作系统。

本项目将十二篇提取为 **11 套独立但互相关联的谋略框架**，每套框架都包含：原文、白话解读、历史案例、现代场景适配、分步执行清单和边界警告。

**这不是国学解读，是谋略工具箱。**

**English:**

*Guiguzi* (鬼谷子) is a classic Chinese text on strategy and persuasion, written over 2,300 years ago. This project distills its 12 chapters into 11 actionable strategy frameworks — each with original text, interpretation, historical cases, modern scenarios, step-by-step execution guides, and boundary warnings.

**This is not a philosophy reading. It's a strategy toolkit.**

---

## 为什么是鬼谷子 | Why Guiguzi

市面上有无数 AI prompt 项目，但绝大多数是英文的、通用的、浅层的。

鬼谷子的谋略体系有三个独特优势：

1. **系统性强**：12篇构成完整的"情报→沟通→关系→策略→决策"操作链，不是零散技巧
2. **可执行性高**：每套框架都有明确的分步操作和判停条件，不是"悟道"式玄学
3. **稀缺性**：中文古典谋略 + 结构化 AI prompt = 市场空白

程序员能写代码，但不一定能把鬼谷子拆成可执行框架。这就是这个项目的壁垒。

---

## 11 套框架一览 | 11 Frameworks

| # | 名称 | 篇章 | 一句话 | 解决什么问题 |
|---|------|------|--------|-----------|
| s01 | 捭阖术 | 捭阖第一 | 信息的开关控制 | 何时说、何时不说、说什么色彩的话 |
| s02 | 反应术 | 反应第二 | 对话中钓取真话 | 怎么把对方的真实想法钓出来 |
| s03 | 内揵术 | 内揵第三 | 关系通道绑定 | 怎么和关键人物建立稳固关系 |
| s04 | 抵巇术 | 抵巇第四 | 裂缝识别与利用 | 怎么发现和利用组织/关系中的裂缝 |
| s05 | 飞箝术 | 飞箝第五 | 赞美与控制 | 怎么用赞美和利益钩子控制局面 |
| s06 | 忤合术 | 忤合第六 | 多边博弈选边站 | 在多方博弈中怎么选阵营 |
| s07 | 揣摩术 | 揣篇第七+摩篇第八 | 系统性情报工程 | 怎么系统性地收集情报、试探底牌 |
| s08 | 权变术 | 权篇第九 | 话术的对象适配 | 对不同的人说不同的话 |
| s09 | 谋术 | 谋篇第十 | 方案生成系统 | 面对变化怎么系统地想出方案 |
| s10 | 决术 | 决篇第十一 | 决策拍板方法 | 多个选项怎么做出最优决策 |
| s11 | 符言九守 | 符言第十二 | 内修与信息管理 | 决策者的自我修养 |

每个框架的结构：`R（原文）→ I（解读）→ A1（案例）→ A2（触发场景）→ E（执行步骤）→ B（边界）`

---

## 快速开始 | Quick Start

### 1. ChatGPT 用户

```bash
# 方式一：Custom Instructions
# 将 prompts/universal-prompt.md 的内容粘贴到 ChatGPT Settings → Custom Instructions

# 方式二：创建 GPT
# 将 prompts/ 内容作为 Instructions，modules/ 文件作为 Knowledge Base
```

详见 [ChatGPT 使用指南](prompts/chatgpt-guide.md)

### 2. Claude 用户

```bash
# 创建 Claude Project
# System Prompt → 粘贴 prompts/universal-prompt.md
# Knowledge → 上传 modules/ 目录下的文件
```

详见 [Claude 使用指南](prompts/claude-guide.md)

### 3. WorkBuddy 用户

```bash
# 将整个项目文件夹放入 skills 目录
cp -r guiguzi-ai-skill ~/.workbuddy/skills/
```

### 4. 直接阅读

每个模块文件（`modules/` 目录）都可以独立阅读，包含完整的框架内容。

---

## 目录结构 | Project Structure

```
guiguzi-ai-skill/
├── README.md                          # 你正在看的这个文件
├── SKILL.md                           # WorkBuddy Skill 主入口
├── LICENSE                            # CC BY-NC-SA 4.0
├── .github/
│   └── FUNDING.yml                    # 赞助配置（爱发电）
├── modules/                           # 11 套框架完整内容
│   ├── s01-bai-he-shu.md              # 捭阖术
│   ├── s02-fan-ying-shu.md            # 反应术
│   ├── s03-nei-jian-shu.md            # 内揵术
│   ├── s04-di-xi-shu.md               # 抵巇术
│   ├── s05-fei-qian-shu.md            # 飞箝术
│   ├── s06-wu-he-shu.md               # 忤合术
│   ├── s07-chuai-mo-shu.md            # 揣摩术
│   ├── s08-quan-bian-shu.md           # 权变术
│   ├── s09-mou-shu.md                 # 谋术
│   ├── s10-jue-shu.md                 # 决术
│   ├── s11-fu-yan-jiu-shou.md         # 符言九守
│   └── s*-test-prompts.json           # 各框架的测试用例
├── prompts/                           # 通用 AI 适配
│   ├── universal-prompt.md            # 通用 System Prompt
│   ├── chatgpt-guide.md              # ChatGPT 使用指南
│   └── claude-guide.md               # Claude 使用指南
├── examples/                          # 使用示例
│   └── example-negotiation.md         # 谈判场景示例
└── docs/
    └── quick-start.md                # 快速上手指南
```

---

## 使用示例 | Example

**问题：** "我下周要见一个潜在投资人，他之前投了我竞品，我该怎么准备？"

**AI 分析（使用 s07 揣摩术 + s03 内揵术）：**

> **框架匹配**：谈判准备场景，主框架 s07 揣摩术（情报收集），辅助 s03 内揵术（关系绑定）。
>
> **Step 1 — 量权（12维度评估）**：
> - 投了竞品说明看好赛道，查他过去12个月投资记录、偏好领域、典型deal size
> - 愿意见你，说明对竞品不是完全满意，或想更了解赛道格局
>
> **Step 2 — 揣情（情绪窗口期）**：
> - 在对话中用"反应术"的沉默和反问，探测他对竞品的真实评价
> - "您投的XX最近发展怎么样？" → 观察他的语气是骄傲还是遗憾
>
> **Step 3 — 内揵（关系通道）**：
> - 判断他是哪种类型的投资人：资源型(道德型)？战略型(智者型)？财务型(贪者型)？
> - 根据类型选择绑定通道：资源型走"道义"通道，战略型走"道理"通道...
>
> **边界提醒**：揣摩术的核心是"微而去之"——探到信息后不要暴露你在收集情报。

完整示例详见 [examples/example-negotiation.md](examples/example-negotiation.md)

---

## 框架关系图 | Framework Relationship

```
内修(s11) → 情报(s07/s02) → 信息控制(s01) → 关系(s03)
→ 机会(s04/s06) → 控制(s05/s08) → 方案(s09) → 决策(s10)
```

11 套框架不是孤立的技巧卡片，而是一条完整的谋略操作链。复杂问题通常需要多框架组合使用。

---

## 谁适合用 | Who is this for

- 创业者 / 商业人士 —— 谈判、竞品分析、投资尽调、合伙人关系
- 职场人 —— 向上管理、跨部门博弈、职业选择
- 投资人 —— 项目尽调、创始人评估、投资决策
- 销售 / BD —— 客户关系、需求挖掘、话术设计
- 任何对博弈论、谈判术、人际策略感兴趣的人

---

## 设计原则 | Design Principles

1. **原文为体，现代为用** —— 忠于原文含义，但不做考据，所有解读指向"今天怎么用"
2. **可执行优先** —— 每个框架都有分步操作清单和判停条件
3. **边界明确** —— 每套框架都标注了"什么时候不要用"和"失败模式"
4. **不装神弄鬼** —— 鬼谷子不是玄学，是一套经过实战检验的博弈方法论
5. **交叉引用** —— 框架之间有明确的关系图谱，复杂问题可以多框架组合

---

## 贡献 | Contributing

欢迎通过 Issues 和 Pull Requests 贡献：

- 报告内容错误或过时描述
- 补充现代案例（商业、职场、科技领域）
- 提供新的使用场景和测试用例
- 改进 AI prompt 适配效果
- 翻译为其他语言

---

## 许可证 | License

本项目采用 [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/) 许可证：

- ✅ **共享** — 可以以任何媒介复制和分发
- ✅ **改编** — 可以修改、转换和在此基础上创作
- ❌ **非商业** — 不得用于商业目的
- ✅ **相同许可** — 衍生作品须采用相同许可证

---

## 支持作者 | Support

如果这个项目对你有帮助，欢迎 Star ⭐ 和分享。

<sub>作者背景：公关策划出身，服务过腾讯、百度等互联网企业，现自由职业者。非程序员，在 AI 辅助下完成此项目——证明 AI 时代，领域知识 + AI 工具 = 新可能。</sub>
