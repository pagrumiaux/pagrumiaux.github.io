# AGENTS.md

Instructions for every coding agent working in this repo. Keep it under ~100 lines: it is loaded into every agent's context. Detail goes in the reference docs below, read only when needed.

## Project
<One paragraph: what this project is.>

## Stack
<5–10 lines: language, framework, database, key libraries, and anything agents must not swap out.>

## Commands
- Install: `<e.g. npm ci>`
- Test: `<e.g. npm test>`
- Lint / format: `<e.g. npm run lint>`
- Run locally: `<e.g. npm run dev>` → `<e.g. http://localhost:3000>`

## Conventions
- <Code style, folder layout, naming.>
- Tests live in `<path>` and use `<framework>`.

## Reference docs
<!-- Project-wide docs, each with when to read it. Task-specific files go in the plan's read_first instead. -->
- `docs/INDEX.md`: every doc section with its size and a one-line summary (made by `lib index --write`). Start here, then read only the section you need with `lib doc <path>#<heading>`.
- `docs/decisions/`: lasting design decisions; `grep -H "^- Area:" docs/decisions/*.md` lists them by area. Check the ones about the area you change.
- `<e.g. docs/tech-stack.md>`: <e.g. read before adding a dependency or changing infrastructure>.

## Workflow rules
Shared by every project: `~/repertoire/rules/workflow.md` (loaded in every session).

## Standards
Language standards: `~/repertoire/standards/<language>.md` (python, typescript). Read the section you need. This AGENTS.md adds only what is specific to the project, beyond the standards.

## Rules from review
<!-- One line per rule, added by R- PRs: "- <rule> (from #<PR>)" -->
