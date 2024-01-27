# Parallel data for Mambai


## Data

Parallel corpus is compiled in `mambai_parallel_data.csv`, with data coming from:
- [Mambai Language Manual.docx](https://docs.google.com/document/d/1RiokF1qnyQw1UY3nA-zchIPbUQ8b7T4e/edit)
- [Mambae STORY BOOKS copy](https://docs.google.com/document/d/1suIRXsg1dZJTY13ss2_xG3nvH8X4u132/edit)
- [Miguel’s Garden](https://docs.google.com/document/d/1-KSYDszYHGHzpJF4N0F5zdLu2T7BmXpw/edit)
- [mambae_ermera_graded_readers](https://docs.google.com/spreadsheets/u/1/d/1V2ePV1E9mZy-RvCR9BdqdARUmxEUpgee/edit?usp=drive_web&ouid=111605484374857807395&rtpof=true)
- [english-mambae-tetun(updated 2014-09-21)](https://docs.google.com/document/u/1/d/1kgTP6Or1T33JlpGpV0WlJbrjSVs5hnM1/edit?usp=drive_web&ouid=111605484374857807395&rtpof=true)

All data manually aligned, apart from Mambai Language Manual.docx, aligned through `extract_mambai_language_manual.ipynb`

## Getting started

1. Setup Python requirements: `python3 -m venv .venv && source .venv/bin/activate && pip install -r requirements.txt`
2. Extract text from Mambai Language Guide: see `mambai parallel text.ipynb`
