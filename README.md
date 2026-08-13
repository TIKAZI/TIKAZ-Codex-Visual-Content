<p align="center"><strong>English</strong> · <a href="README.zh-CN.md">简体中文</a></p>

<p align="center"><img src="assets/hero.svg" alt="TIKAZ Visual Content for Codex" width="100%" /></p>

<h1 align="center">TIKAZ Visual Content for Codex</h1>
<p align="center"><strong>Provider-neutral illustration, concise writing, and lawful music workflows with publishing QA.</strong></p>
<p align="center"><a href="https://github.com/TIKAZI/TIKAZ-Codex-Visual-Content/actions/workflows/validate.yml"><img src="https://github.com/TIKAZI/TIKAZ-Codex-Visual-Content/actions/workflows/validate.yml/badge.svg" alt="Validate" /></a> <a href="LICENSE"><img src="https://img.shields.io/badge/license-MIT-f4c95d.svg" alt="MIT" /></a> <img src="https://img.shields.io/badge/version-0.8.0-F472B6.svg" alt="0.8.0" /></p>
<p align="center"><a href="https://github.com/TIKAZI/TIKAZ-AI-Skills">← Explore all seven TIKAZ AI Skills for Codex suites</a></p>

---

## ✨ One suite, ready to install

This repository is the independently installable **visual-content** distribution from [TIKAZ AI Skills for Codex](https://github.com/TIKAZI/TIKAZ-AI-Skills). The monorepo is the canonical development source; this repository is automatically synchronized and optimized for people who need only this workflow.

Designed, integrated, refactored, and continuously maintained by **TIKAZ**; community contributions are welcome. This is an independent project, not an OpenAI-official repository.

This repository is an automatically synchronized distribution of the canonical [TIKAZ-AI-Skills](https://github.com/TIKAZI/TIKAZ-AI-Skills) monorepo. Cross-suite issues and source changes belong in the canonical repository.

## 🧩 What makes it different

- **One visual identity and one shot card own each asset**
- **Chinese labels, factual claims, alt text, and publishing-size legibility are verified**
- **Music discovery retains license and attribution evidence**

## 📦 Install

Clone or download this repository, then copy the repository folder into the Skill directory supported by your Codex environment. The root `SKILL.md` is the suite orchestrator; child folders are focused Skills that can also be installed separately.

```bash
git clone https://github.com/TIKAZI/TIKAZ-Codex-Visual-Content.git
```

## 🧩 Use one Skill independently

Every Skill below has its own promise, installation command, example, execution contract, limits, and bilingual project page:

- [`concise-writing-editor`](https://tikazi.github.io/TIKAZ-AI-Skills/skills/concise-writing-editor/index.html)
- [`legal-free-music`](https://tikazi.github.io/TIKAZ-AI-Skills/skills/legal-free-music/index.html)
- [`visual-content`](https://tikazi.github.io/TIKAZ-AI-Skills/skills/visual-content/index.html)
- [`xiaohei-article-illustrator`](https://tikazi.github.io/TIKAZ-AI-Skills/skills/xiaohei-article-illustrator/index.html)
- [`zhuge-logistics-illustrator`](https://tikazi.github.io/TIKAZ-AI-Skills/skills/zhuge-logistics-illustrator/index.html)

## 🚀 Try it

```text
Turn this essay into one original hand-drawn metaphor with a shot card, verified Chinese labels, and alt text.
```

```text
Explain this warehouse process as a sourced 16:9 logistics diagram with aligned nodes and explicit exceptions.
```

```text
Remove filler from this caption, then find lawful music and retain the download and attribution evidence.
```

## 🔄 How the suite works

Read [SKILL.md](SKILL.md) for the owning workflow, [references/routing.md](references/routing.md) for specialist routing, and [references/output-contract.md](references/output-contract.md) for the verified handoff. Optional tools are detected at runtime; local login state or machine-specific software is never promised as universally available.

## 🗂️ Repository structure

```text
./
├─ SKILL.md                 # suite orchestrator
├─ agents/                  # Codex UI metadata
├─ references/              # routing and output contract
├─ <child-skill>/           # independently installable specialists
├─ DISTRIBUTION.yml         # canonical source and sync metadata
└─ scripts/                 # deterministic validation
```

## ⚖️ Canonical source and contributions

Development, source review, and cross-suite architecture live in [TIKAZ-AI-Skills](https://github.com/TIKAZI/TIKAZ-AI-Skills). This distribution synchronizes from `suites/visual-content` every week and can also be refreshed manually through GitHub Actions.

Source modes, observed licenses, and concrete TIKAZ contributions are recorded in [SOURCES.yml](SOURCES.yml) and [THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md). TIKAZ-authored files are released under the [MIT License](LICENSE).

## 🌐 Explore the TIKAZ workflow family

[🏠 AI Skills](https://github.com/TIKAZI/TIKAZ-AI-Skills) · [⚡ Context Economy](https://github.com/TIKAZI/TIKAZ-Codex-Context-Economy) · [🎨 Frontend Design](https://github.com/TIKAZI/TIKAZ-Codex-Frontend-Design) · [🎬 Video Intelligence](https://github.com/TIKAZI/TIKAZ-Codex-Video-Intelligence) · [🛠️ Engineering](https://github.com/TIKAZI/TIKAZ-Codex-Engineering) · [🔬 Research](https://github.com/TIKAZI/TIKAZ-Codex-Knowledge-Research) · [📽️ Presentation](https://github.com/TIKAZI/TIKAZ-Codex-Presentation) · [🖼️ Visual Content](https://github.com/TIKAZI/TIKAZ-Codex-Visual-Content)
