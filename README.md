# NLP Notebooks

This repository contains Jupyter notebooks showcasing various NLP techniques, including text processing, classification, sentiment analysis, and topic modeling. The notebooks are part of the assessments from the Udemy course [Natural Language Processing with Python](https://www.udemy.com/course/nlp-natural-language-processing-with-python/).

## Table of Contents

- [NLP Basics](#nlp-basics)
- [Parts of Speech (POS) Analysis](#parts-of-speech-pos-analysis)
- [Text Classification](#text-classification)
- [Sentiment Analysis and Vector Arithmetic](#sentiment-analysis-and-vector-arithmetic)
- [Topic Modeling with Latent Dirichlet Allocation (LDA)](#topic-modeling-with-latent-dirichlet-allocation-lda)
- [Topic Modeling with Non-negative Matrix Factorization (NMF)](#topic-modeling-with-non-negative-matrix-factorization-nmf)

## NLP Basics

### Description
Explores basic NLP tasks with the short story [_An Occurrence at Owl Creek Bridge_](https://en.wikipedia.org/wiki/An_Occurrence_at_Owl_Creek_Bridge), including token counting, sentence extraction, and phrase matching.

### File
- `1-NLP-Basics.ipynb`

## Parts of Speech (POS) Analysis

### Description
Analyzes parts of speech in [The Tale of Peter Rabbit](https://en.wikipedia.org/wiki/The_Tale_of_Peter_Rabbit) by Beatrix Potter, covering token attributes, POS frequency, and named entities.

### File
- `2-POS.ipynb`

## Text Classification

### Description
Classifies movie reviews as positive or negative using a TF-IDF vectorizer and a linear SVM classifier. Evaluates performance with a confusion matrix and classification report.

### File
- `3-Text-Classification.ipynb`

## Sentiment Analysis and Vector Arithmetic

### Description
Performs sentiment analysis with VADER and vector arithmetic with SpaCy. Includes cosine similarity calculations and finding the closest vectors to given word expressions.

### File
- `4-Sentiment-Analysis_and_Vector-Arithmetic.ipynb`

## Topic Modeling with Latent Dirichlet Allocation (LDA)

### Description
Uses LDA to identify topics in NPR articles. Features preprocessing, topic extraction, and labeling of discovered topics.

### File
- `5.1-Topic_Modeling-Latent-Dirichlet-Allocation.ipynb`

## Topic Modeling with Non-negative Matrix Factorization (NMF)

### Description
Applies NMF to cluster Quora questions into categories. Includes TF-IDF vectorization, topic extraction, and labeling of topics.

### File
- `5.2-Topic_Modeling-NMF.ipynb`

## Files Directory

The `files` directory contains the datasets and text files used in the notebooks. Ensure you have the following files in this directory:

- `owlcreek.txt`: The text file for the NLP Basics notebook.
- `peterrabbit.txt`: The text file for the POS Analysis notebook.
- `moviereviews2.tsv`: The dataset for the Text Classification notebook.
- `npr.csv`: The dataset for the LDA topic modeling notebook.
- `quora_questions.csv`: The dataset for the NMF topic modeling notebook.

Make sure these files are correctly placed in the `files` directory for the notebooks to function properly.

## Getting Started

### Prerequisites
- Python 3.8+
- Jupyter Notebook
- Required Python libraries (specified in `requirements.txt`)

### Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/TouradBaba/nlp-notebooks.git
    ```
2. Navigate to the directory:
    ```bash
    cd nlp-notebooks
    ```
3. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```

### Usage
1. Open the desired notebook in Jupyter Notebook.
2. Follow the instructions and execute the cells to perform the tasks.
