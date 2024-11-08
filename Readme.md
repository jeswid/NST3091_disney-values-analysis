####Quantitative Methods for Disney Social Values Analysis
###Project Overview
This repository contains the codes used for analyzing how social values, such as female empowerment, racial inclusivity, and moral values, are portrayed in Disney movies over time. The project aims to provide both qualitative and quantitative insights into Disney's narrative strategies and their evolution across different film eras.

The analysis incorporates methods such as thematic coding, regression modeling, and BERT-based textual classification.

###Table of Contents
Background
Methodology
Files
Contributors

###Background
Disney movies have influenced societal perspectives on gender roles, racial inclusivity, and morality. This study examines how these portrayals have evolved through the Classics, Renaissance, and New Age eras of Disney films.

###Objectives:
1. Identify trends in the portrayal of female empowerment, racial inclusivity, and moral values.
2. Conduct qualitative analysis using movie scripts and quantitative analysis using box office data.
3. Address research gaps with longitudinal analysis of Disney’s narrative changes over time.

###Methodology
##Qualitative Analysis
Thematic Coding: Classification of Disney films based on the presence and portrayal of specific social values using a modified tick-and-cross matrix method.
##Quantitative Analysis
Regression Modeling: Log-linear regressions were employed to understand correlations between movie portrayals and regional box office earnings.
BERT Model: Pre-trained BERT models were used to derive confidence scores for the portrayal of key values in film scripts.
Topic Modeling: Latent Dirichlet Allocation (LDA) was utilized to identify hidden topics within film scripts.

###Files
data/: Contains data files, including movie scripts and the corresponding box office earnings data.
NLP/: Includes Python scripts used for conducting topic modelling and zero shot classification of movies into values
Regression/: Include STATA do files for conducting log-linear regressions

###Contributors
Teo Jer Rei
Nguyen Phuong Chi
Jessica Widyawati

