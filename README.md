# Naive Bayes Classifier for Fake News Recognition

**Coursework project · Advanced Statistics for Physics Analysis · Physics of Data, University of Padova**

## Overview

Fake news and misinformation spread readily through social media, often mixing subtly with
legitimate content. This project builds a Multinomial Naive Bayes classifier in R to
automatically flag likely misinformation in social media posts, and evaluates it rigorously
against tuned baselines.

## Data

Kaggle fake-news dataset: 10,240 labeled training instances and 1,267 test instances of
social media/news text.

## Method

- Text preprocessing and document-term matrix construction (`CorpusToDtm`)
- **Multinomial Naive Bayes** implemented with the `e1071` R package
- Train/test split with stratification on class labels
- Hyperparameter tuning via grid search (binomial and multinomial variants compared)
- Evaluation on accuracy and computation time across configurations

## Technical skills

| Area | Details |
|---|---|
| NLP | Text preprocessing, document-term matrices, corpus construction |
| Machine learning | Multinomial Naive Bayes, grid search, cross-validation |
| R | `e1071`, statistical modeling, data wrangling |

## Repository note

Coursework project for the "Advanced Statistics for Physics Analysis" module, Physics of
Data Master's degree, University of Padova.
