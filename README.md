# Skills

This repository is organized as an MD-first skills library, following the same structure used by benchmark repos such as:

- https://github.com/mattpocock/skills

The goal is to keep each skill easy to read, easy to share, and easy to extend.

## Structure

```text
README.md
SKILL_TEMPLATE.md
skills/
  state-gatekeeper/
    SKILL.md
  diagnostician/
    SKILL.md
```

## How this repo works

- Each skill lives in its own folder under `skills/`
- Each skill file is named `SKILL.md`
- The skill description should include:
  - trigger conditions
  - objective
  - workflow
  - output format
  - rules and constraints
  - optional notes for future refinement

## Why MD-first

This format is useful because it is:

- easy to browse on GitHub
- easy to share with others
- simple to fork and remix
- consistent with public skill repos

## Adding a new skill

1. Create a new folder under `skills/`
2. Add a `SKILL.md` file
3. Copy the structure from `SKILL_TEMPLATE.md`
4. Update this README only if you want to add a new category or note

## Notes

This repository is intentionally centered on markdown skills. If you later decide to add code, scripts, or automation, that can be added in a separate layer without changing the core skill format.
