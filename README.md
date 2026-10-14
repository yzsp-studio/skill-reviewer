<div align="center">

# 🎬 skill-reviewer

## 上架前 4 道检查，描述不行当场拦下
## Four pre-publish gates: weak descriptions get blocked on the spot

📮 **商务合作 / Business：wow.vip@foxmail.com**
🎬 **抖音 / Douyin：[v.douyin.com/07EjIDGVErY](https://v.douyin.com/07EjIDGVErY/)**

</div>

---

## 🇨🇳 中文

Skill 质量审查工具，审查 SKILL.md 的结构、描述质量、触发词覆盖度，以及 meta.yaml 展示字段是否符合 Hub 最新上架规范（字数、分类枚举、中英对齐、命名禁用词）。它是只读的：分析并报告，永远不修改文件。审查从定位与阅读 SKILL.md 开始，先验证结构与 frontmatter 必填项，再评估最关键的一项——描述，最后评估内容质量，并给出评分和优先改进建议。适合在 Skill 上架前或迭代后做一次体检。

### ✨ 能做什么

- 只读审查：只分析报告，绝不修改文件
- 定位并阅读 SKILL.md 的 frontmatter 与正文，检查 references/、scripts/ 支持目录
- 验证结构：name/description 必填、正文 ≤500 行、编号步骤、标题与介绍段落
- 评估描述质量（最关键）与触发词覆盖度
- 校验 meta.yaml 上架规范：字数、分类枚举、中英对齐、命名禁用词
- 输出评分与优先改进建议

### 📦 包含的技能

- `skill-reviewer` —— 见 [`skill-reviewer/SKILL.md`](skill-reviewer/SKILL.md)

### 🚀 安装

```bash
git clone https://github.com/yzsp-studio/skill-reviewer.git
cp -r skill-reviewer/* "$DSH_HOME/skills/"
```

> 技能是**纯文本说明**（`SKILL.md` + `references/`），零依赖、零 API key，用你当前 agent 的会话额度。

---

## 🇬🇧 English

A quality-review tool for Skills: it audits the structure of SKILL.md, the quality of its description, the coverage of its trigger words, and whether the meta.yaml display fields meet the latest marketplace listing rules (character counts, category enum, Chinese-English alignment, prohibited words in names). It is strictly read-only — it analyzes and reports and never edits files. Review starts by locating and reading SKILL.md, verifies structure and required frontmatter fields, then evaluates the most critical item, the description, before assessing content quality and returning a score with prioritized fixes. Use it as a checkup before publishing a Skill or after iterating on one.

### ✨ What it does

- Read-only review: it analyzes and reports, never edits files
- Locates and reads SKILL.md frontmatter and body, and checks for references/ and scripts/ support directories
- Validates structure: required name/description, body under 500 lines, numbered steps, title and intro
- Scores description quality (the most critical part) and trigger-word coverage
- Checks meta.yaml listing rules: character counts, category enum, Chinese-English alignment, banned words in names
- Returns a score plus prioritized improvement suggestions

### 📦 Skills included

- `skill-reviewer` — [`skill-reviewer/SKILL.md`](skill-reviewer/SKILL.md)

### 🚀 Install

```bash
git clone https://github.com/yzsp-studio/skill-reviewer.git
cp -r skill-reviewer/* "$DSH_HOME/skills/"
```

> Skills are **plain-text instructions** (`SKILL.md` + `references/`). Zero dependencies, no API keys — they run on your agent's existing session quota.

---

## 📮 联系 / Contact

| | |
|---|---|
| 🎬 **抖音 / Douyin** | [https://v.douyin.com/07EjIDGVErY/](https://v.douyin.com/07EjIDGVErY/) |
| 📮 **商务合作 / Business** | **wow.vip@foxmail.com** |
| 🐙 **GitHub** | [https://github.com/yzsp-ai](https://github.com/yzsp-ai) |
| 💖 **打赏 / Support** | [afdian.com/a/yzsp-ai](https://afdian.com/a/yzsp-ai) |

## 📄 License

[MIT](LICENSE) · © 2026 [yzsp-ai](https://github.com/yzsp-ai)
