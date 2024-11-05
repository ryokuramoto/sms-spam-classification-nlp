# SMS Spam Classification using Natural Language Processing (NLP)

This repository contains a Jupyter Notebook that demonstrates how to classify SMS messages as either "spam" or "ham" (non-spam) using Natural Language Processing (NLP) techniques and machine learning. The SMS Spam Collection dataset from the UCI Machine Learning Repository is used for this task.

## Table of Contents
- [Files](#files)
- [Getting Started](#getting-started)
- [Google Colab](#google-colab)
- [License](#license)
- [Contact](#contact)

## Files

### Dataset
- `SMSSpamCollection`: A tab-separated file containing SMS messages labeled as "spam" or "ham." This dataset is sourced from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/sms+spam+collection#).

### Code
- `sms_spam_classification_nlp.ipynb`: A Jupyter Notebook containing the full workflow for SMS spam classification. This includes data preprocessing, text vectorization, model building using RandomForest, and model evaluation.

## Getting Started

To use the notebook in this repository, follow these steps:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/ryokuramoto/sms-spam-classification-nlp.git
   cd sms-spam-classification-nlp
   ```

2. **Install the required libraries:**  
   Ensure you have Python installed. You can install the required libraries by running:
   ```bash
   pip install numpy pandas matplotlib seaborn nltk scikit-learn
   ```
   
3. **Open the notebook:**
   Use Jupyter Notebook, Jupyter Lab, or Google Colab to open and run `sms_spam_classification_nlp.ipynb`.

## Google Colab

You can open the notebook directly in Google Colab by clicking the "Open in Colab" button below:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ryokuramoto/sms-spam-classification-nlp/blob/main/sms_spam_classification_nlp.ipynb)

### Saving Your Work
- **To save a copy to Google Drive**: Navigate to `File > Save a copy in Drive`.
- **To save a copy locally**: Navigate to `File > Download`.

## License

The dataset is licensed under the [Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/) license. This project, including the notebook, is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
