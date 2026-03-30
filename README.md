# Arabic-to-English Literary Translator

A Claude Code skill for Arabic-to-English literary translation with built-in AI-pattern removal (humanizer).

## What it does

Translates Arabic text into natural, publication-ready English using a three-phase workflow:

1. **Deep Analysis** — Identifies text type, register, rhetorical devices (البلاغة), cultural references, emotional arc, root resonances, and translation traps before writing a single English word
2. **Two-Pass Translation** — Analytical draft preserving Arabic structure, then natural adaptation for English idiom and rhythm
3. **Polish and Humanize** — Three sweeps (translation artifacts, AI pattern removal, voice/soul) plus a two-pass anti-AI audit

## Features

- Handles all Arabic registers: MSA, Classical/Quranic, Egyptian, Gulf, Levantine, literary, technical
- 14 Arabic rhetorical devices with specific English compensation strategies
- 25+ banned AI vocabulary words and pattern detection (based on Wikipedia's "Signs of AI writing")
- Register-aware translation that preserves shifts between formal and colloquial
- Nida's "equivalent effect" as the guiding principle

## Installation

Copy the `arabic-translator/` folder (with `SKILL.md` and `references/`) into your Claude Code skills directory:

```
~/.claude/skills/arabic-translator/
├── SKILL.md
└── references/
    └── rhetoric-guide.md
```

## Usage

Provide Arabic text and the skill triggers automatically. You can also use:
- "translate this"
- "ترجم"
- "Arabic to English"

Optional metadata: author/source, text type, dialect, target reader familiarity (high/moderate/low), terminology to preserve.

## Version

v3 — Deep analysis workflow + integrated humanizer (25 AI patterns)