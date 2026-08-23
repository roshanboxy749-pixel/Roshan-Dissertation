# Consumer Perceptions of Sustainability: Sentiment Analysis Project

## Project Overview

This repository contains the analytical materials developed for an MSc Business Analytics research project examining consumer perceptions of sustainability-related products, brands and practices using sentiment extracted from online textual data.

The project applies Natural Language Processing (NLP), supervised machine-learning techniques and sentiment analysis to investigate how consumer perceptions vary across different sustainability-related topics.

## Research Question

How do consumers perceive sustainability-related products, brands and practices based on sentiment extracted from online textual data?

## Dataset

The study uses the EcoForumFeedbackDataset developed by Ferdinand Mahardhika and Tutur Wicaksono (2025) and published through Mendeley Data.

The original dataset contains 3,523 manually collected public comments from Kaskus, Quora, Reddit and Twitter covering sustainability-related discussions between 2015 and 2025. The comments are provided in English and Bahasa Indonesia and are manually annotated using Positive, Negative and Neutral sentiment labels.

Following language filtering, text cleaning, duplicate removal and preprocessing, 1,180 English-language comments were retained for the final analysis.

Dataset:
EcoForumFeedbackDataset

Authors:
Ferdinand Mahardhika and Tutur Wicaksono

Published:
2025

DOI:
10.17632/hftnm6dtsp.1

## Analytical Approach

The analysis was conducted in Python using a Jupyter Notebook. The analytical workflow included:

- Data cleaning and preprocessing
- English-language filtering
- Tokenisation, stop-word removal and lemmatisation
- TF-IDF feature extraction
- Logistic Regression
- Multinomial Naïve Bayes
- LinearSVC
- Model evaluation using accuracy, precision, recall and F1-score
- Hyperparameter optimisation using GridSearchCV
- VADER sentiment analysis
- Topic-level sentiment analysis

## Repository Contents

This repository contains:

- The dataset used for the research
- The final Jupyter Notebook containing the complete Python analysis
- This README file describing the project, dataset and analytical workflow

## Reproducibility

The Jupyter Notebook documents the analytical workflow from data preprocessing through machine-learning evaluation, VADER sentiment analysis and topic-level analysis. The dataset and analytical code are provided to support transparency and reproducibility of the research.

## Software and Libraries

The analysis was conducted using Python in Jupyter Notebook. Key libraries used include:

- pandas
- NumPy
- scikit-learn
- NLTK
- matplotlib
- seaborn

## Academic Purpose

This repository was developed as supporting technical documentation for an MSc Business Analytics research project at the University of Greenwich.
