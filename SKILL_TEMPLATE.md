# Skills Repository Template

This repository follows the same MD-first pattern as the benchmark repo:

- https://github.com/mattpocock/skills

The core idea is simple:

- skills are stored as markdown documentation
- each skill lives in its own folder
- the repository is organized for easy browsing and reuse
- optional scripts or code can be added later, but they are not required

## Recommended structure

```text
README.md
CONTRIBUTING.md
SKILL_TEMPLATE.md
skills/
  skill-name/
    SKILL.md
  another-skill/
    SKILL.md
```

## Best practice for each skill

Each skill file should include:

- name
- trigger conditions
- objective
- workflow
- output format
- examples
- constraints / rules
- notes for future extension

## Recommended skill file layout

```md
# Skill Name

## Trigger

When this skill should be used.

## Goal

What the skill is trying to achieve.

## Workflow

1. Step one
2. Step two
3. Step three

## Output format

```text
Something structured here
```

## Rules

- Rule 1
- Rule 2
- Rule 3

## Notes

Any caveats, edge cases, or future improvements.
```

## How to add a new skill

1. Create a new folder under `skills/`
2. Name it clearly and consistently
3. Add a `SKILL.md` file inside
4. Use the template in `SKILL_TEMPLATE.md`
5. Update README if needed

## Why MD-first

MD-first repos are easier to:

- browse in GitHub
- share with others
- copy and remix
- standardize across teams

This works especially well for workflow and reasoning skill libraries.
