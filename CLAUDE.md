# CLAUDE.md

Guidance for Claude Code (and other AI assistants) working in this repository.

> **⚠️ SCAFFOLD — NOT YET FILLED IN**
>
> This file was generated while the repository was still empty (no commits, no
> source files). Every section below is a placeholder. **Nothing here has been
> verified against real code, because there is no code yet.**
>
> Do not treat the headings below as descriptions of how this project actually
> works. As the codebase lands, replace each `TODO` with facts checked against
> the repository, and delete this banner once the file reflects reality.
>
> If you are an AI assistant and a section still says `TODO`, you have no
> guidance for that topic — inspect the codebase directly and, ideally, fill the
> section in as part of your change.

## Project overview

TODO: One paragraph on what this project is, who uses it, and the problem it
solves. Include anything non-obvious about the domain that a newcomer would
otherwise have to reverse-engineer.

## Tech stack

TODO: Languages, runtime versions, frameworks, package manager, database, and
any pinned versions that matter (e.g. a `.nvmrc`, `pyproject.toml` constraint,
or toolchain file). Prefer pointing at the authoritative file over restating
version numbers that will drift.

## Repository layout

TODO: Map the top-level directories and say what belongs in each — the kind of
orientation that saves a search. Example shape:

```
src/          TODO
tests/        TODO
scripts/      TODO
```

Note anything surprising: generated directories, vendored code, or paths that
should never be edited by hand.

## Development setup

TODO: The exact commands to go from a fresh clone to a running project.

```bash
# install dependencies
# TODO

# run the app
# TODO
```

Also record required environment variables and where they come from (a
`.env.example`, a secrets manager, a teammate). Never commit real secrets.

## Common commands

TODO: Fill in the commands contributors actually run. Delete rows that don't
apply rather than leaving guesses.

| Task | Command |
| --- | --- |
| Install deps | TODO |
| Run dev server | TODO |
| Run tests | TODO |
| Run a single test | TODO |
| Lint | TODO |
| Format | TODO |
| Type check | TODO |
| Build | TODO |

The single-test command is worth getting right — it is the fastest feedback
loop available and AI assistants should use it instead of running the full
suite on every edit.

## Testing

TODO: Test framework, where tests live, naming conventions, and what level of
coverage is expected for a new change. State explicitly whether a change is
considered done without tests.

## Code style and conventions

TODO: Formatter and linter config (point at the config files rather than
duplicating rules), naming conventions, import ordering, error-handling
patterns, and any house rules a linter does not catch.

General rule that applies regardless: match the surrounding code. Read
neighboring files before introducing a pattern that is new to this repo.

## Architecture notes

TODO: The handful of design decisions that are expensive to infer from reading
files — module boundaries, data flow, where state lives, why an unusual choice
was made. Keep this short and current; a stale architecture section is worse
than none.

## Git workflow

TODO: Confirm or correct the following once the team has settled on a process.

- Default branch: TODO (the repository currently has no branches)
- Branch naming: TODO
- Commit message format: TODO (e.g. Conventional Commits, or freeform)
- Are PRs required, and who reviews: TODO
- CI checks that must pass before merge: TODO

## CI/CD

TODO: What runs on push and on PR, where the config lives, and how deploys
happen. Note anything an assistant could break without noticing locally.

## Gotchas

TODO: The things that waste an afternoon — flaky tests, required local
services, ordering dependencies in setup, files that look editable but are
generated. This section earns its keep faster than any other.

## Instructions for AI assistants

- Verify before you assert. If this file disagrees with the code, the code
  wins — and the file should be corrected in the same change.
- Prefer the narrowest command that gives feedback (single test over full
  suite) while iterating.
- Do not add dependencies without checking what is already available in the
  manifest.
- Do not commit secrets, credentials, or `.env` files.
- Keep this file updated when you change something it describes: commands,
  layout, or workflow.
