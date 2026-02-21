# Data Science Day 2026

Each notebook is self-contained works in **JupyterLab**

---

## Notebooks

| # | Topic | Concepts |
|---|-------|----------|
| 01 | Monty Hall Problem | Probability, simulation|
| 02 | Birthday Paradox | Combinatorics, probability|
| 03 | Titanic Survival | Data exploration, ML |
| 04 | Word Embeddings | vectors, cosine similarity, PCA |

---

## Project Structure

```
DataScienceDay2026/
├── .venv/               # Virtual environment (managed by uv)
├── data/
│   ├── titanic.csv              # 891 Titanic passengers (from seaborn)
│   ├── wiki-news-300d-1M.vec    # FastText 300-dim word vectors (1M words)
│   └── wiki-news-300d-1M.vec.zip
├── notebooks/
│   ├── 01_monty_hall.ipynb
│   ├── 02_birthday_paradox.ipynb
│   ├── 03_titanic.ipynb
│   └── 04_word_embeddings.ipynb
├── pyproject.toml
└── README.md
```

---

## Setup

Requires [uv](https://docs.astral.sh/uv/). Install it once if you don't have it:

```bash
pip install uv
```

Then, from the project folder:

```bash
uv sync
```

This creates `.venv/` and installs all dependencies automatically.

---

## Running the Notebooks

```bash
uv run jupyter lab
```

Open any notebook from the `notebooks/` folder in the browser that opens.
