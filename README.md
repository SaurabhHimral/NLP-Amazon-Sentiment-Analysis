Amazon Alexa Review - Sentiment Analysis

This project analyzes the Amazon Alexa dataset and builds machine learning models to predict whether a given review has a positive or negative sentiment.

📌 Project Overview

Performed Exploratory Data Analysis (EDA) to understand the dataset.

Preprocessed text using tokenization, stopword removal, and stemming.

Engineered features such as review length.

Trained and evaluated multiple machine learning models.

Visualized results using confusion matrices and accuracy scores.

⚙️ Technologies & Libraries Used

Python 3.x

Jupyter Notebook

Pandas, NumPy (data handling)

Matplotlib, Seaborn (visualization)

NLTK (text preprocessing)

Scikit-learn (feature extraction, model training & evaluation)

📂 Project Structure
├── Data Exploration & Modelling.ipynb   # Main Jupyter Notebook
├── README.md                            # Project Documentation
├── data/                                # Dataset (if included)
└── requirements.txt                     # Dependencies

🚀 How to Run

Clone the repository:

git clone https://github.com/SaurabhHimral/NLP-Amazon-Sentiment-Analysis/tree/main.git
cd amazon-alexa-sentiment


Create a virtual environment and activate it:

python -m venv venv
source venv/bin/activate   # On Linux/Mac
venv\Scripts\activate      # On Windows


Install dependencies:

pip install -r requirements.txt


Open the Jupyter Notebook:

jupyter notebook


Run Data Exploration & Modelling.ipynb.

📊 Results

Built and compared classification models.

Best-performing model achieved high accuracy in sentiment classification.

Confusion matrices were used to analyze performance.

🔮 Future Improvements

Try deep learning models (e.g., LSTMs, Transformers).

Deploy the model as a web app using Flask/Streamlit.

Experiment with word embeddings (Word2Vec, GloVe, BERT).