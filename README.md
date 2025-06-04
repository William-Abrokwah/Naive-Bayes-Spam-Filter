# 📩 Naive Bayes Spam Filter

A simple spam detection tool using the Naive Bayes algorithm. This project classifies SMS as "spam" or "ham" (not spam) based on their content.

## Table of Contents

- [📌 Overview](#📌overview)
- [🚀 Features](#🚀-features)
- [⚙️ Installation](#⚙️-installation)
- [📂 Dataset](#📂-dataset)
- [💡 Contributing](#💡-contributing)
- [📝 License](#📝-license)

## 📌 Overview
This project implements a spam detection system using a Multinomial Naive Bayes classifier. It processes SMS text messages to classify them as spam or ham (not spam) by leveraging natural language processing techniques and machine learning.

## 🚀 Features

- Text preprocessing: Includes tokenization, removing punctuation, and filtering out stopwords
- Feature extraction: Uses Bag-of-Words representation with CountVectorizer to convert text into numeric data
- Model training: Trains a Multinomial Naive Bayes classifier on labeled SMS messages
- Evaluation: Measures model performance using accuracy, precision, recall, and F1-score
- Visualization: Provides histograms and plots to explore message length distributions and word frequencies
- Interactive predictions: Allows users to input custom SMS messages and get real-time spam/ham classification

## ⚙️ Installation

Running the Project
1. Clone this repository
```bash
git clone https://github.com/William-Abrokwah/Naive-Bayes-Spam-Filter.git
cd Naive-Bayes-Spam-Filter
```
2. Set up and activate your virtual environment and install requirements
```bash
python -m venv env

# On Windows:
env\Scripts\activate

# On macOS/Linux:
source env/bin/activate

pip install -r requirements.txt
```
3. Run the Jupyter notebook Spam_Filter.ipynb to explore the data, train the model, and visualize results
4. Use the provided prediction function to classify new messages

## 📂 Dataset

This project uses the SMS Spam Collection Dataset from UCI, hosted on Kaggle.

## 🛠️ Tech Stack / Tools

- Python
- Pandas
- NumPy
- NLTK
- scikit-learn
- Seaborn / Matplotlib (for visualizations)
- Jupyter Notebook

## 💡 Contributing

If you'd like to contribute to this project, please feel free to open issues or submit pull requests. For major changes, please open an issue first to discuss what you would like to change.

## 📝 License

This project is licensed under the MIT License. See the LICENSE file for more details.