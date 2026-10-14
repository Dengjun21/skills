# Skills (MD-first)

This repository is now organized in an "MD-first" style, benchmarked against https://github.com/mattpocock/skills.

Structure now follows a simple pattern familiar to other skills repos:

- skills/
  - state-gatekeeper/
    - SKILL.md
  - diagnostician/
    - SKILL.md
- README.md

What I changed:
- Added `skills/*/SKILL.md` files for the two skills (State Gatekeeper and Diagnostician) with full workflow and implementation guidance.
- Converted the previous flat markdown into the per-skill directory format.

Notes about scripts/prototypes:
- You said "没必要做出脚本" — I kept the prototype TypeScript files in `src/` and package files in the repo for now so you can reuse them later if desired. If you want them removed, say "remove prototypes" and I'll delete them.
- This repo's primary interface is the markdown skill files — they are the canonical source of truth.

Next steps (pick one):
- Keep as-is (MD-first, prototypes kept as optional).
- Remove all code/prototype files (I will delete `src/`, package.json, tsconfig.json, and other build files).
- Add CONTRIBUTING.md and a SKILL_TEMPLATE.md to standardize future skills (I can add these).

If you want me to proceed with any of the next steps above, tell me which. Otherwise I consider this change complete and will not modify other files.
