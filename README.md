# interview-simulator： AI面试模拟器

## 项目简介
AI面试模拟器是一个让应聘者在面试之前，使用AI进行模拟面试来对自己的面试能力进行查缺补漏。

## 模式支持

**模式一：参考答案对比**
- AI 根据职位描述（JD）和用户简历，分别扮演 HR 面试官 或 业务/技术面试官 进行提问。
- AI 同时提供同一问题的 高分回答 与 普通回答，帮助用户直观理解差距。

**模式二：回答优化对比**
- AI 同样扮演对应类型的面试官进行提问。
- 用户先作答，AI 随后给出参考回答。
- 系统对两次回答进行评估对比，提供优化建议或在用户原回答基础上进行改进。

## 安装

### 方法一：通过 npx 一键安装（推荐）

```bash
npx skills add https://github.com/Cocoon-break/interview-simulator.git
```

这是最简单的安装方式，会自动将技能安装到正确的目录。

### 方法二：通过 Git 克隆

```bash
# 克隆到 Claude Code 的 skills 目录
git clone https://github.com/Cocoon-break/interview-simulator.git ~/.claude/skills/interview-simulator
```
