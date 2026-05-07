# Contributing

## Commit Messages

This repository uses Conventional Commits.

Use this shape:

```text
<type>(optional-scope): <description>
```

Common types:

- `feat`: add a new note, training page, or published capability.
- `fix`: correct inaccurate documentation or broken site behavior.
- `docs`: update public documentation content.
- `chore`: maintain project structure, tooling, or repository metadata.
- `refactor`: reorganize content without changing meaning.

Examples:

```text
docs: add session 01 theory notes
chore: scaffold public training notes
fix: correct langsmith environment variable name
```

## Public vs Local Work

Only commit the Hugo site, notes, and project documentation.

Do not commit cloned training repositories, executed notebooks, generated outputs, or
secret-bearing environment files. Keep that work under `practice/` or another ignored
local folder.
