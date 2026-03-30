# Arabic Translator

Arabic-to-English literary translation skill for Claude Code with built-in humanizer.

Combines deep Arabic rhetoric analysis (balagha), register-aware translation, and AI-pattern removal in one workflow.

## Install

```bash
mkdir -p ~/.claude/skills
git clone https://github.com/almuthanawork/arabic-translator.git ~/.claude/skills/arabic-translator
```

## Usage

In Claude Code, type `/arabic-translator` followed by your Arabic text, or just ask Claude to translate Arabic text and the skill will activate automatically.

## What it does

- 6-phase translation process: deep reading, first draft, reflection, refinement, humanizer pass, final verification
- Handles 11 Arabic rhetorical devices (balagha) with specific English compensation strategies
- Register-aware: fusha, ammiya (all dialects), literary, Quranic, and mixed registers
- Built-in AI-pattern removal ensures the English output reads like human-written prose
- Passes three quality tests: monolingual beauty, bilingual accuracy, author voice recognition

## Structure

```
arabic-translator/
├── SKILL.md                          # Main skill instructions
└── references/
    ├── rhetoric-guide.md             # Balagha device handling (11 devices)
    └── humanizer-checklist.md        # AI pattern removal checklist
```

## License

MIT
