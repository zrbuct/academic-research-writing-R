# Academic Research Writing - Codex Skill

从 [Leey21/awesome-ai-research-writing](https://github.com/Leey21/awesome-ai-research-writing) 衍生而来的 Codex skill，汇集了一线科研人员（MSRA、Seed、SH AI Lab、北大、中科大、上交）实战打磨的学术论文写作资源。

## 包含内容

### 16 类 Prompt 模板
翻译（中↔英，LaTeX/Word）、润色、缩写/扩写、去AI味、逻辑检查、图表标题生成、实验分析、审稿人视角审稿、模型选择等。

### Agent Skills 生态指南
论文写作相关的五大 skills（20-ml-paper-writing、humanizer、docx、docx、doc-coauthoring、canvas-design）的配置方式与使用场景。

## 安装

通过 Codex skill-installer：
```bash
python scripts/install-skill-from-github.py --repo <your-username>/academic-research-writing --path .
```

或直接克隆：
```bash
git clone https://github.com/<your-username>/academic-research-writing.git ${CODEX_HOME:-~/.codex}/skills/academic-research-writing
```

重启 Codex 后生效。

## 使用

在 Codex 中直接描述需求即可触发，例如：
- "帮我把这段中文翻译成英文论文"
- "用 reviewer 视角审一下这篇论文"
- "给这张图写个符合 ICML 规范的 caption"
