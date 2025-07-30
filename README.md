# Sentiment Analysis 🧠💬

This repository contains code and datasets for a sentiment analysis project implemented in Python. The goal is to classify textual data (such as reviews) into positive or negative sentiment using machine learning and natural language processing (NLP) techniques.
It was a project assignment in the edx course "MITx: Machine Learning with Python: from Linear Models to Deep Learning".

## 📁 Repository Structure

📦 sentiment-analysis/

├── 200.txt # Sample dataset or stopword/wordlist file

├── 4000.txt # Sample dataset or stopword/wordlist file

├── README.md # Project overview (you're reading it!)

├── main.py # Main execution file for sentiment classification

├── reviews_submit.tsv # TSV file for submission (likely test set predictions)

├── reviews_test.tsv # Test dataset

├── reviews_train.tsv # Training dataset

├── reviews_val.tsv # Validation dataset

├── stopwords.txt # List of stopwords used for text preprocessing

├── test.py # Script for testing modules or experiments

├── tmp_project1.py # Temporary or experimental project file

├── toy_data.tsv # Smaller or synthetic dataset for quick testing

├── utils.py # Utility functions for preprocessing and model handling


## 🚀 Features

- Text preprocessing (stopword removal, tokenization, etc.)
- Support for training/validation/test splits
- Model training and evaluation
- Utility functions for modular pipeline design
- Easily configurable for different datasets

## 🛠️ How to Run

1. Clone the repository:
    ```bash
    git clone https://github.com/anushkarao12/sentiment-analysis.git
    cd sentiment-analysis
    ```

2. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```
    *(Note: You may need to create a `requirements.txt` using `pip freeze > requirements.txt`.)*

3. Run the main script:
    ```bash
    python main.py
    ```

4. (Optional) Run tests or experiments:
    ```bash
    python test.py
    ```

## 📊 Datasets

The project uses `.tsv` (tab-separated values) files for input datasets:
- `reviews_train.tsv`: Labeled data for training the model
- `reviews_val.tsv`: Labeled data for validation during training
- `reviews_test.tsv`: Unlabeled or test data for prediction
- `toy_data.tsv`: Simplified dataset for rapid testing
- `reviews_submit.tsv`: Possibly the final test predictions

## 📌 To Do

- [ ] Add model performance metrics and logs
- [ ] Include Jupyter Notebook for EDA (Exploratory Data Analysis)
- [ ] Improve preprocessing and lemmatization pipeline
- [ ] Add support for deep learning models (e.g., LSTM or BERT)

## 🧠 Tech Stack

- Python 3.x
- pandas
- scikit-learn
- NLTK / spaCy (if used in utils)
- NumPy

## 📜 License

This project is open-source and freely available under the MIT License.

---

Feel free to contribute, star ⭐ the repo, or fork 🍴 to build your own version!
