# Quantitative Methods for Disney Social Values Analysis

## Project Overview

This repository contains the codes used for analyzing how social values, such as **female empowerment, racial inclusivity, and moral values**, are portrayed in Disney movies over time. The project aims to provide both **qualitative** and **quantitative** insights into Disney's narrative strategies and their evolution across different film eras.

---

## Table of Contents

- [Background](#background)
- [Methodology](#methodology)
- [Files](#files)
- [Installation](#installation)
- [Contributors](#contributors)

---

## Background

Disney movies have influenced societal perspectives on gender roles, racial inclusivity, and morality. This study examines how these portrayals have evolved through **the Classics, Renaissance, and New Age eras** of Disney films.

### Objectives:

1. Identify trends in the portrayal of **female empowerment, racial inclusivity, and moral values**.
2. Conduct **qualitative** analysis using movie scripts and **quantitative** analysis using box office data.
3. Address research gaps with **longitudinal analysis** of Disney’s narrative changes over time.

---

## Methodology

### Qualitative Analysis

- **Thematic Coding**: Classification of Disney films based on the presence and portrayal of specific social values using a modified tick-and-cross matrix method.

### Quantitative Analysis

- **Regression Modeling**: Log-linear Poisson regression was employed to understand correlations between movie portrayals and regional box office earnings.
- **BERT Model**: Pre-trained BERT models were used to derive confidence scores for the portrayal of key values in film scripts.
- **Topic Modeling**: Latent Dirichlet Allocation (LDA) was utilized to identify hidden topics within film scripts.

---

## Files

- `data/`: Contains data files, including movie scripts and box office earnings data.
- `NLP/`: Includes Python scripts used for topic modelling and zero-shot classification.
- `regressions/`: Includes STATA do files used for regressions.
- `README.md`: This file.

---

## Installation

1. Clone this repository:
    ```bash
    git clone https://github.com/your-username/disney-values-analysis.git
    ```
2. Navigate to the repository directory:
    ```bash
    cd disney-values-analysis
    ```
---

## Contributors

1. Teo Jer Rei - teojerrei2000@gmail.com
2. Nguyen Phuong Chi - npchi1101@gmail.com
3. Jessica Widyawati - jessicawidyawati@gmail.com

