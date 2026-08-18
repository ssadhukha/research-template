# Project Name

Short description of what this project does.

## Structure

```
data/       # source + derived data (large files gitignored, DataLad-managed)
code/       # reusable code / pipeline modules
analyses/   # notebooks + analysis scripts
docs/       # notes, papers, data dictionaries
figs/       # generated figures
env.yml     # conda environment
```

## Setup

```bash
conda env create -f env.yml
conda activate project-name
```
