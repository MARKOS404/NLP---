# NLP Paraphrase & Similarity Assignment

This repository contains the implementation and report for the NLP assignment on **paraphrase generation** and **semantic similarity evaluation** using modern Transformer-based models (T5, BART, DistilBART).

## 📂 Contents
- `analysis.ipynb`: Jupyter notebook with experiments, metrics and visualizations
- `report.docx`: Final written report (can also be exported as PDF)
- `pyproject.toml` / `poetry.lock`: Poetry project dependencies
- `assets/`: Folder with images (PCA, t-SNE, etc.)
- `.gitignore`: Excludes sensitive or unnecessary files

## ⚙️ Installation

### Using Poetry
```bash
poetry install
poetry run jupyter notebook analysis.ipynb
