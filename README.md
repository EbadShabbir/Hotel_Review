# Deceptive Opinion Detection Using SVM

This project focuses on detecting deceptive opinions using Support Vector Machines (SVM) with text data. The dataset is preprocessed, vectorized using TF-IDF, and classified using a linear SVM model.

---

## Table of Contents

1. [Overview](#overview)  
2. [Dataset](#dataset)  
3. [Installation](#installation)  


---

## Overview

Deceptive opinion detection is a critical task in natural language processing. This repository implements a supervised machine learning pipeline to classify text as deceptive or truthful using the following steps:
- Data preprocessing (lowercasing, punctuation removal)
- Text vectorization using TF-IDF
- Classification using Support Vector Machines (SVM)
- Evaluation through accuracy, classification report, and confusion matrix

---

## Dataset

The dataset used for this project can be found in the file `deceptive-opinion.csv`. It contains the following columns:
- `text`: The text data to classify.
- `deceptive`: The target label (e.g., deceptive or truthful).

Ensure the dataset is placed in the directory `/kaggle/input/deception-opinion/` or adjust the path in the code accordingly.

---

## Installation

Clone this repository and install the required libraries:

```bash
git clone <repository-url>
cd <repository-directory>
pip install -r requirements.txt
