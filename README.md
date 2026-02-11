# 🤖 Agent Skills

Reusable AI agent skills for vibe coding. Install with a single command to enhance your AI agents with procedural knowledge.

## 📦 Available Skills

| Skill | Description |
|-------|-------------|
| [powerapps-yaml](./powerapps-yaml/) | Generate paste-ready YAML for Power Apps Studio using pa.yaml Schema v3. Includes modern controls, cache patterns, Gallery with collections, and SharePoint backend patterns. |

## 🚀 Installation

### Via [skills.sh](https://skills.sh)

```bash
npx skills install matiaslbeltranu/agent-skills
```

### Manual Installation

Copy the skill folder into your agent's skills directory:

```bash
# For Gemini CLI / Antigravity
cp -r powerapps-yaml/ ~/.gemini/antigravity/skills/

# For Claude Code
cp -r powerapps-yaml/ ~/.claude/skills/
```

## 🤝 Contributing

Want to add a new skill? Create a new folder with a `SKILL.md` file following the format of the existing skills.

## 📄 License

MIT
