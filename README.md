# review-ratings-NLPinsights
NLP-based analysis of P&amp;G customer reviews using multiple models to predict review ratings from text. Built as a learning tool to explore the data analytics process and identify the most effective predictive model for use by ND Data Club.

# P&G Customer Review NLP Analysis

This project explores customer reviews of Procter & Gamble (P&G) products using Natural Language Processing (NLP) techniques and multiple machine learning models. The goal is to understand trends in the data, build predictive models for review ratings, and identify the most effective model for future use by the ND Data Club.

### 🌐 Project Goals

Extract insights from P&G customer reviews using NLP

Predict review ratings from textual data

Compare multiple models (Logistic Regression, Random Forest, RoBERTa, etc.)

Visualize patterns and trends in review content and sentiment

Learn and document the end-to-end data analytics process

## 📊 Dataset

The dataset contains customer review data from P&G products, including:

brand: Product brand name

review_title: Title of the review

review_text: Full review content

review_rating: Numeric rating from 1 to 5

and more columns 

## 🚀 Models Used

Logistic Regression

RoBERTa-base (via HuggingFace Transformers)

Optional experimentation with pipeline pre-built models

## 🔄 Workflow

Data Preprocessing

Text cleaning

Tokenization

Vectorization (TF-IDF, embeddings)

Model Training/Prem-trained setups

Train/test split

Hyperparameter tuning

Cross-validation

Evaluation

Trend analysis

Visualization

## 📚 Learning Outcome

This project is designed to deepen understanding of:

Text-based predictive modeling

Model comparison and evaluation

Practical data preprocessing

Communication of findings through visualizations

## 🧱 For ND Data Club

The final goal is to determine the most robust model for predicting review ratings from raw text to support future projects and student learning within the ND Data Club community.

## ⚙️ How to Run
```
# Clone the repo
https://github.com/yourusername/p-and-g-review-analysis.git
cd p-and-g-review-analysis

# (Optional) create and activate virtualenv
python3 -m venv venv
source venv/bin/activate

# Install dependencies
pip install -r requirements.txt

# Launch Jupyter
jupyter notebook
```
## 📁 Repo Structure
```

.
├── data/                   # Raw and cleaned CSV files
├── example.ipynb           # Jupyter notebooks for EDA and modeling
├── images/                 # Generated plots and word clouds
├── requirements.txt        # Dependencies
├── README.md               # This file
```
📚 License

This project is licensed under the MIT License.

Feel free to fork and use as a starting point for your own text analysis work!
