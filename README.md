# Low-Resource Machine Translation through Retrieval-Augmented LLM Prompting: A Study on the Mambai Language


## Data

- Training data used for prompting compiled in [`mambai_parallel_eng_mgm.csv`](./mambai_parallel_eng_mgm.csv), with data coming from the Mambai Languaage Manual. The `split` column can be `train` or `test`
- Additional test data compiled from a native Mambai speaker compiled in `test_leo.json`

From the Mambai Language Manual, dictionaries have also been extracted through `extract_mambai_dict.ipynb` and stored in [`eng_mgm.json`](./eng_mgm.json) and [`mgm_eng.json`](./mgm_eng.json)

These dictionaries were used to mine bitext from the Mambai Language Manual through hunalign, see `extract_mambai_parallel.ipynb`.

## Getting started

1. Setup Python requirements: `python3 -m venv .venv && source .venv/bin/activate && pip install -r requirements.txt`
2. Extract text from Mambai Language Guide: see `extract_mambai_parallel.ipynb` and `extract_mambai_dict.ipynb`
3. Run translation experiments - see below

## Translation

See notebook [`Mambai_prompt_for_MT.ipynb`](./Mambai_prompt_for_MT.ipynb). Tweak parameters in the `config` dict to adjust hyper parameters.
