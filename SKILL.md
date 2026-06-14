---
name: academic-research-writing
description: Academic research paper writing assistant for Chinese/English scholarly writing. Provides battle-tested prompt templates for translation (CN↔EN, LaTeX/Word), academic polishing, condensing, expanding, de-AI-ifying, logic checking, experiment analysis, figure/table caption generation, reviewer-perspective review, data visualization recommendations, and model selection guide. Also covers the paper-writing agent skills ecosystem (OpenSkills, Cursor). Use when the user needs help with academic paper writing, polishing, translation between Chinese and English, reviewing drafts, generating figure/table captions, analyzing experiment results, or seeking guidance on AI tools for research writing.
---

# Academic Research Writing

Battle-tested prompt templates and agent skills ecosystem for Chinese/English academic paper writing, sourced from researchers at MSRA, Seed, SH AI Lab, Peking University, USTC, SJTU.

## Quick navigation

- **Prompt templates** → [references/prompts.md](references/prompts.md) — 18 curated prompts for every stage of paper writing
- **Agent skills ecosystem** → [references/skills-ecosystem.md](references/skills-ecosystem.md) — OpenSkills setup, skill catalog, and usage scenarios

## When to load references

Always load [references/prompts.md](references/prompts.md) when the user asks for:
- Translation: Chinese ↔ English (LaTeX or Word format)
- Polishing or rewriting academic text (English or Chinese)
- Condensing or expanding paragraphs
- Logic checking or de-AI-ifying text
- Figure/table caption generation
- Experiment data analysis and writeup
- Reviewer-perspective paper review
- Model recommendations for research writing
- Data visualization strategy

Load [references/skills-ecosystem.md](references/skills-ecosystem.md) when the user asks about:
- Setting up or using Codex/Cursor agent skills for paper writing
- Available skills for research writing (20-ml-paper-writing, humanizer, docx, doc-coauthoring, canvas-design)
- Specific workflows like starting a new paper from a repo, migrating between conference templates, or structured co-authoring

## How to use the prompts

Each prompt in the reference is a self-contained template. When the user describes a task:

1. Identify which prompt category matches their need
2. Read the corresponding prompt from the reference
3. Adapt the prompt as needed — fill in the user's actual content at the [Input] marker
4. Execute the prompt directly in the current conversation or present it for the user to use

The prompts are designed to produce multi-part output (e.g., Part 1: Result, Part 2: Translation/Log). Respect this structure unless the user asks otherwise.

## Key prompt categories

| Task | Prompt Section |
|------|---------------|
| CN→EN translation (LaTeX) | 中转英-latex |
| EN→CN translation (LaTeX) | 英转中-latex |
| CN→EN translation (Word) | 中转英-word |
| CN polishing (Word, Chinese) | 中转中-word / 表达润色（中文论文） |
| EN polishing | 表达润色（英文论文） |
| Condense text | 缩写 |
| Expand text | 扩写 |
| Logic check | 逻辑检查 |
| Remove AI writing traces | 去 AI 味（LaTeX 英文）/ 去 AI 味（Word 中文） |
| Figure/table captions | 生成图的标题 / 生成表的标题 |
| Experiment analysis | 实验分析 |
| Reviewer review | 论文整体以 Reviewer 视角进行审视 |
| Data visualization | 实验绘图推荐 |
| Architecture diagrams | 论文架构图 |
| Model selection | 模型选择 |
