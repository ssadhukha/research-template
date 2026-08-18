# CLAUDE.md

Context for Claude Code when working in this repo.

## What this project is

<one-line description>

## Layout

- `code/` — reusable modules; import from here, don't copy between notebooks.
- `analyses/` — notebooks + analysis scripts that consume `code/`.
- `data/` — large data is gitignored; don't try to commit it.
- `figs/` — generated figures.
- `docs/` — notes, papers, data dictionaries.

## Environment

- `conda env create -f env.yml && conda activate project-name`
- Key deps: <list your project's key dependencies here>.

## Conventions

- Raw data is immutable — write derived data elsewhere, never overwrite it.
