# rvc-notation — Agent Instructions

Part of the RVC ecosystem. **Read [rvc-ecosystem/AGENTS.md](https://github.com/petercorke/rvc-ecosystem/blob/main/AGENTS.md) first** — it defines shared conventions: repo ownership, math invariants, dependency boundaries, git/PR workflow, code standards, tech-debt tracking. This file only adds what's specific to this repo.

| | |
|---|---|
| PyPI package | none — LaTeX document, not a Python package |
| Nickname | rvc-notation |
| Owner | Peter Corke (`petercorke`) |
| Default branch | `master` (pending migration to `main`) |
| Contribution model | Branch → PR; direct push to `master` at Peter's discretion |

## Notes specific to this repo

- Shared mathematical notation reference for the ecosystem — LaTeX only, no code. The
  ecosystem's "Code Standards" sections (type hints, docstrings, etc.) don't apply here; the
  math invariants (§2 of the ecosystem `AGENTS.md`) are the relevant part.
- Notation changes here have ripple effects on docstring math notation across RTB/MVTB/bdsim —
  flag anything that would require updating LaTeX in those repos' docs.
- Several other repos' Sphinx `conf.py` (RTB, MVTB, bdsim docs) define a MathJax mirror of
  these LaTeX macros, so equations in the online docs render using the same notation as the
  book. Changing a macro here means checking those `conf.py` mirrors too, not just this repo.
