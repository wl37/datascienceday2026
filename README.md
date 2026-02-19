# Data Science Day 2026

Each notebook is self-contained works in **JupyterLab**

---

## Notebooks

| # | Topic | Concepts |
|---|-------|----------|
| 01 | Monty Hall Problem | Probability, simulation, counter-intuition |
| 02 | Birthday Paradox | Combinatorics, probability curves |
| 03 | Titanic Survival | Data exploration, decision trees, ML |
| 04 | Word Embeddings | NLP, vectors, cosine similarity, PCA |

---

## Project Structure

```
DataScienceDay2026/
├── .venv/               # Virtual environment (managed by uv)
├── data/
│   ├── titanic.csv      # 891 Titanic passengers (from seaborn)
│   └── glove_sample.csv # 80 words × 50-dim word vectors (8 semantic clusters)
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

---

## Dependencies

| Package | Purpose |
|---------|---------|
| jupyterlab | Development / code walkthrough |
| pandas, numpy | Data manipulation |
| matplotlib, seaborn | Visualization |
| scikit-learn | Decision tree, PCA |
| ipywidgets | Interactive sliders, dropdowns, buttons |
| pillow | Image support |
