# Movies SQL Python Lab

SQLite and Python lab for importing movie records and running SELECT, JOIN, and GROUP BY queries.

## Overview

**Curricular code:** P02  
**Discipline:** Data Storage, Manipulation, and Transformation I  
**Difficulty:** Introductory  
**Dataset reference:** TMDB-style movies sample  
**Primary source:** https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata

This repository is an educational portfolio project for the first module of a technical Data Science curriculum. It uses a small safe sample by default and provides a script that documents how a real public dataset could be obtained or prepared later.

No large dataset, private school document, real student record, or personal contact detail is versioned in this repository.

## Concepts Practiced

- sqlite3
- tables
- primary keys
- SELECT
- GROUP BY

## Repository Structure

```text
data/
  sample/       # small safe sample used by smoke tests
  raw/          # external raw files, ignored except .gitkeep
  processed/    # generated outputs, ignored except .gitkeep
notebooks/
  01_exploracao.ipynb
scripts/
  download_data.py
src/
  main.py
charts/
reports/
```

## Quick Start

```bash
python -m venv .venv
.venv\Scripts\activate
pip install -r requirements.txt
python -m src.main --sample
```

Linux/macOS activation:

```bash
source .venv/bin/activate
```

## Data Policy

- The default workflow uses only sample data committed to `data/sample/`.
- Real public datasets should be downloaded manually or through `scripts/download_data.py` after reviewing the source terms.
- Generated outputs are written to `data/processed/`, `charts/`, or `reports/`.

---

# Movies SQL Python Lab

SQLite and Python lab for importing movie records and running SELECT, JOIN, and GROUP BY queries.

## Visao Geral

**Codigo curricular:** P02  
**Disciplina:** Armazenamento, Manipulacao e Transformacao de Dados I  
**Dificuldade:** Introdutorio  
**Referencia de dataset:** TMDB-style movies sample  
**Fonte primaria:** https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata

Este repositorio e um projeto educacional de portfolio para o primeiro modulo de um curso tecnico em Ciencia de Dados. Ele usa uma amostra pequena e segura por padrao e traz um script que documenta como um dataset publico real poderia ser obtido ou preparado depois.

Nenhum dataset grande, documento interno escolar, registro real de estudante ou contato pessoal e versionado neste repositorio.

## Conceitos Praticados

- sqlite3
- tables
- primary keys
- SELECT
- GROUP BY

## Como Rodar

```bash
python -m venv .venv
.venv\Scripts\activate
pip install -r requirements.txt
python -m src.main --sample
```

## Politica De Dados

- O fluxo padrao usa apenas dados de amostra em `data/sample/`.
- Datasets publicos reais devem ser baixados manualmente ou por `scripts/download_data.py` apos revisao dos termos da fonte.
- Saidas geradas ficam em `data/processed/`, `charts/` ou `reports/`.

## License

MIT. See [LICENSE](LICENSE).
