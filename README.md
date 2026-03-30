# NLP Course Work 3

This repository contains the code and data for Coursework 3: experiments in language modeling and POS-tagging on tweet data.

**What’s included** <!--markdownlint-disable-line-->

- Notebooks: `notebooks/local_language_modeling_pos.ipynb`, `notebooks/colab_language_modeling_pos.ipynb`
- Data: `data/raw/training.1600000.processed.noemoticon.csv` (Sentiment140-derived tweets)
- Dependencies: `requirements.txt`

## **Quick start — clone & setup**

1. Clone the repo:

```bash
    git clone https://github.com/Hansen256/NLP_coursework_3.git
    cd NLP_coursework_3
```

1. Create and activate a Python virtual environment (Windows PowerShell):

```bash
    python -m venv .venv
    .\.venv\Scripts\Activate.ps1
```

```bash
    (On CMD use `\.venv\Scripts\activate.bat`)
```

1. Install dependencies:

```bash
    pip install -r requirements.txt
```

1. Data: the dataset is under `data/raw/`. If you need to download or replace it, put the CSV at `data/raw/training.1600000.processed.noemoticon.csv`.

## **Running the notebooks**

- Open the project in Jupyter or VS Code and run either notebook in `notebooks/`.
- For Colab, use `colab_language_modeling_pos.ipynb` (some cells may assume Colab runtime adjustments).
