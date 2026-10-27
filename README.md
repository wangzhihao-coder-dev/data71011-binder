# data71011-binder

DATA71011 Understanding Data and their Environment — Week 5 Lab #1 (Zero-to-Binder reproducibility exercise).

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/wangzhihao-coder-dev/data71011-binder/HEAD)

- `hello.py` — minimal script (`python hello.py`)
- `requirements.txt` — Python dependencies installed by Binder
- `postBuild` — downloads `gapminder.csv` (Oceania GDP per capita) when the image is built

## Environment

Package versions in `requirements.txt` are pinned to the exact versions that Binder installed on 2026-10-27
(`pip freeze`): numpy 1.25.0, pandas 2.3.3, matplotlib 3.10.9.
