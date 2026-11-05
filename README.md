# product-review-absa
## Overview
This project implements Aspect-Based Sentiment Analysis (ABSA) on product reviews. The objective is to identify aspects discussed in customer reviews and classify the sentiment associated with them.

The project combines Latent Dirichlet Allocation (LDA) for topic modeling with machine learning and deep learning approaches for sentiment classification.
## Publication
This project is based on research published in an international journal.

- **Paper Title:** Does Topic-Based Aspect Labeling Improve Sentiment Analysis? A Comparative Study of LDA-Guided Segmentation with BERT and TF-IDF
- **Journal:** Ingénierie des Systèmes d’Information 
- **Publication Year:** 2026
- **DOI:** [10.18280/isi.310427](https://doi.org/10.18280/isi.310427)
- **Publication Link:** https://iieta.org/journals/isi/paper/10.18280/isi.310427

## Project Workflow
**1. Baseline Sentiment Classification** – Establish baseline performance using TF-IDF with Logistic Regression and BERT.

**2. Topic Modeling** – Apply Latent Dirichlet Allocation (LDA) to identify topics within product reviews.

**3. Automatic Label Annotation** – Assign topic labels to reviews based on the LDA results.

**4. Aspect-Based Sentiment Classification** – Perform sentiment classification for each identified aspect using Logistic Regression and BERT.

## Methods and Technologies

- **Topic Modeling:** Latent Dirichlet Allocation (LDA)
- **Feature Extraction:** TF-IDF
- **Machine Learning:** Logistic Regression
- **Deep Learning:** BERT
- **Data Handling:** Pandas, NumPy
- **NLP:** Gensim, NLTK
- **Frameworks:** Scikit-learn, Hugging Face Transformers
