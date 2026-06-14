# Academic Research Writing - Codex Skill

从 [Leey21/awesome-ai-research-writing](https://github.com/Leey21/awesome-ai-research-writing) 衍生而来的 Codex skill，汇集了一线经管科研人员实战打磨的学术论文写作资源。

## 包含内容

### 16 类 Prompt 模板
翻译（中↔英）、润色、缩写/扩写、去AI味、逻辑检查、图表标题生成、实验分析、审稿人视角审稿、模型选择等。

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

## 贡献

欢迎大家一起完善这个 skill！

### 方式一：提交 Prompt 模板

如果你有好用的学术写作 prompt，可以直接编辑 `references/prompts.md` 添加进去，发 PR 即可。

### 方式二：Fork → 修改 → Pull Request

1. Fork 本仓库
2. Clone 你的 fork：`git clone https://github.com/<你的用户名>/academic-research-writing-R.git`
3. 创建分支：`git checkout -b my-update`
4. 修改后提交：`git commit -m "添加了xxx场景的prompt"`
5. Push 并到原仓库发起 Pull Request

### 贡献内容建议

- 新的写作场景 prompt（如 rebuttal、cover letter、graphical abstract 等）
- 现有 prompt 的优化和修正
- 新的论文写作相关 skill 或工具推荐
- 多学科适配（目前偏 CS，欢迎其他学科的同学补充）
