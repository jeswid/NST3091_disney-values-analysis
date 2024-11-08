Quantitative Methods for Disney Social Values Analysis
Project Overview
This repository contains the codes used for analyzing how social values, such as female empowerment, racial inclusivity, and moral values, are portrayed in Disney movies over time. The project aims to provide both qualitative and quantitative insights into Disney's narrative strategies and their evolution across different film eras.

The analysis incorporates methods such as thematic coding, regression modeling, and BERT-based textual classification.

Table of Contents
Background
Methodology
Files
Installation
Usage
Contributors
License

Background
Disney movies have influenced societal perspectives on gender roles, racial inclusivity, and morality. This study examines how these portrayals have evolved through the Classics, Renaissance, and New Age eras of Disney films.

Objectives:
Identify trends in the portrayal of female empowerment, racial inclusivity, and moral values.
Conduct qualitative analysis using movie scripts and quantitative analysis using box office data.
Address research gaps with longitudinal analysis of Disney’s narrative changes over time.

Methodology
Qualitative Analysis
Thematic Coding: Classification of Disney films based on the presence and portrayal of specific social values using a modified tick-and-cross matrix method.
Quantitative Analysis
Regression Modeling: Log-linear Poisson regression was employed to understand correlations between movie portrayals and regional box office earnings.
BERT Model: Pre-trained BERT models were used to derive confidence scores for the portrayal of key values in film scripts.
Topic Modeling: Latent Dirichlet Allocation (LDA) was utilized to identify hidden topics within film scripts.

Files
data/: Contains data files, including scripts and box office earnings data.
scripts/: Includes Python scripts used for data cleaning, analysis, and modeling.
bert_classification.py: Code for BERT-based classification of movie scripts.
poisson_regression.R: Log-linear Poisson regression analysis.
topic_modeling.py: Topic modeling using LDA.
README.md: This file.
