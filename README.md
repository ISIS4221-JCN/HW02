# Natural Language Processing - HomeWork 02
This repository gathers the notebooks developed to answer the second task of
ISIS4221-Natural Language Processing 2021-10.

The instructions are available in _HW01-ISIS4221.pdf_.

## Dataset
The datasets used in this implementation are:
1. 20NewsGroups (20N).
2. The Blog Authorship Corpus (BAC).
3. Multi-Domain Sentiment Dataset.
4. Mourning tweets.

## Developers
* Juan David García Hernández (jd.garciah@uniandes.edu.co)
* Nicolás Rocha Pacheco (n.rocha11@uniandes.edu.co)
* César Daniel Garrido Urbano (cd.garrido@uniandes.edu.co)

## Contents
1. N-Gram Language Models Implementation.
  1. 20N N-Gram Model.
  2. BAC N-Gram Model.
2. Naive Bayes (NB) and Logistic Regression.
3. Sentiment Analysis
4. Mourning tweets.

## Data folder structure
The following description states how the data folder should be arranged in order
for it to work directly as instructed in each of the notebooks.

data
+-- SA
| +-- all
| +-- books
|   +-- negative.review
|   +-- positive.review
|   +-- unlabeled.review
|   +-- raw_negative.review
|   +-- raw_positive.review
|   +-- raw_unlabeled.review
| +-- dvd
|   +-- negative.review
|   +-- positive.review
|   +-- unlabeled.review
|   +-- raw_negative.review
|   +-- raw_positive.review
|   +-- raw_unlabeled.review
| +-- electornics
|   +-- negative.review
|   +-- positive.review
|   +-- unlabeled.review
|   +-- raw_negative.review
|   +-- raw_positive.review
|   +-- raw_unlabeled.review
| +-- kitchen
|   +-- negative.review
|   +-- positive.review
|   +-- unlabeled.review
|   +-- raw_negative.review
|   +-- raw_positive.review
|   +-- raw_unlabeled.review
+-- EN_Lexicons
| +-- AFINN-111.txt
| +-- senticnet5.py
| +-- SentiWordNet_3.0.0.txt
| +-- WordStatSentiemnts.txt
+-- 20news
| +-- Folder per category containing correspondent files
