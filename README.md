# skills

A collection of skills for AI coding agents, created and adapted to my needs.

Skills follow the [Agent Skills](https://skills.sh) format and are compatible with
**Claude Code**, **Cursor**, **Codex**, **OpenCode**, and more.

## Installation

```sh
npx skills add dwhoban/skills
```

### Install a specific skill

```sh
npx skills add dwhoban/skills --skill example-skill
```

### List available skills without installing

```sh
npx skills add dwhoban/skills --list
```

## Available Skills

| Name | Description |
|------|-------------|
| [example-skill](./skills/example-skill/SKILL.md) | An example skill template |

## Adding New Skills

Each skill lives in its own directory under `skills/` and requires a `SKILL.md` file:

```
skills/
  my-skill/
    SKILL.md
    scripts/   (optional)
    references/ (optional)
```

To scaffold a new skill:

```sh
npx skills init my-skill
```

## License

MIT
