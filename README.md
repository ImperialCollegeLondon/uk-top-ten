# UK Top Ten Singles

[![Open in GitHub Codespaces](https://github.com/codespaces/badge.svg)](https://codespaces.new/ImperialCollegeLondon/uk-top-ten?quickstart=1)

This repository is the starting point for the UK Top Ten project in the ECRI Research Computing and Data Science hackathon. The project instructions are on the [hackathon wiki](https://github.com/ImperialCollegeLondon/prices/wiki/Projects).

## Quickstart

Open a Codespace with the button above, which has everything set up already. Or, with Python 3.10 or later and Git:

```bash
git clone https://github.com/ImperialCollegeLondon/uk-top-ten.git
cd uk-top-ten
python -m venv .venv
source .venv/bin/activate
python -m pip install -e ".[dev]"
```

## Data

The folder `data/raw` contains the Wikipedia pages "List of UK top-ten singles in 2015" to "List of UK top-ten singles in 2025", one HTML file per year, downloaded from Wikipedia's REST API on 19 October 2026. For example, `2024.html` is [List of UK top-ten singles in 2024](https://en.wikipedia.org/wiki/List_of_UK_top-ten_singles_in_2024).

Each page lists every single which reached the top ten of the UK Singles Chart that year, with the week it entered the top ten, the number of weeks it spent there, its highest position and the week it got there.

The text of these pages is available under the [Creative Commons Attribution-ShareAlike 4.0 licence](https://creativecommons.org/licenses/by-sa/4.0/). If you share data derived from them, credit Wikipedia and use the same licence.
