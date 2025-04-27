# CS4650 Final Project: Binary Sentiment Analysis on IMDb Reviews #

**Overview:**
This project implements and compares three approaches to binary sentiment classification of movie reviews:

- Fine-tuning a pretrained transformer model (DistilBERT)

- Naive Bayes with Bag-of-Words representation

- Majority Class Baseline

Our goal was to evaluate performance across deep learning and traditional methods using the same dataset and metrics.

**Dataset:**
We used the IMDb Movie Reviews Dataset. 
This consisted of:
- 50,000 total labeled movie reviews (positive or negative)

- Balanced classes

- Dataset access: IMDb Dataset on Hugging Face

For efficient training, we sampled:

- 2,000 reviews for training

- 1,000 reviews for testing (shuffled beforehand to avoid label imbalance)

**Files:**

<mark>NLPproject.ipynb</mark>: Final Jupyter Notebook containing code and results

<mark>NLP_Project_Report.pdf</mark>: Project report with methodology, evaluation, and discussion

<mark>README.md</mark>: Project overview and instructions
