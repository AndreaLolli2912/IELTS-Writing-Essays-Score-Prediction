# IELTS Writing Essay Score Prediction

![GitHub contributors](https://img.shields.io/github/contributors/andrealolli13/IELTS-Writing-Essays-Score-Prediction)

## Project Overview

This project was created as our Natural Language Processing (NLP) exam project, made in collaboration with [user 1] and [user 2]. If you're considering working or studying abroad, you may need to prove your language proficiency. In English-speaking countries, this often means passing an English language proficiency test.

## The Need for Automated Essay Grading

In the field of education, assessing student performance is crucial. Traditionally, this assessment relies on manual evaluation by teachers. However, with the increasing student-to-teacher ratio, manual assessment becomes complex, time-consuming, and less reliable.

To address these challenges, online examination systems have emerged for multiple-choice questions. However, grading essays and short answers still lacks a robust automated evaluation system.

## Our Solution

Recognizing these issues, we, as students, took on the challenge to find a solution. Leveraging our expertise in natural language processing (NLP), we developed a model inspired by global research. Our aim was to enhance essay grading by extracting and analyzing various aspects of essays, including relevance, structural organization, semantics, syntax, and grammar.

## Project Goals

Our project's primary goal is to create a model that predicts essay scores using the CEFR grading system. We use a dataset comprising text production from IELTS writing examinations.

## Methodology

To achieve our goal, we employed Natural Language Processing techniques for text preprocessing and extracted meaningful features from the text to enrich our dataset. Our final dataset was used to train a model comprising two layers of Bidirectional GRUs followed by a vanilla neural network.

To assess our model's performance, we experimented with different types of embeddings, including those computed from our textual data, PPMI, TF-IDF, and GloVe. Additionally, we conducted hyperparameter tuning and compared our models with a state-of-the-art algorithm, BERT.

## Getting Started

To replicate our project, you will need the following dependencies:

- [Dataset Link](https://www.kaggle.com/datasets/mazlumi/ielts-writing-scored-essays-dataset)
- [GloVe Embedding](https://drive.google.com/drive/folders/18DakChwcXiTXS-R6aeVZwow5F-s0ZSeB?usp=sharing](https://drive.google.com/drive/folders/12NuXjRZvx4lEq58CRrlGBXohKidRe5wX?usp=sharing))

## Contributors

- [Valentina Bitetto](https://github.com/valentinabitetto)
- [Ana Suarez](https://github.com/Ana91119)


## Acknowledgments

We'd like to express our gratitude to the research community for their contributions to the field of NLP and essay grading.

Feel free to customize this template further to suit your project's unique needs.
