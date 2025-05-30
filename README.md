# TM_G18: Text Mining (G18)

TM_G18 is a natural language processing project focused on three core tasks: Named Entity Recognition and Classification (NERC), sentiment analysis, and topic classification. It uses a variety of models including CRFs, logistic regression, BERT, and ELECTRA to analyze textual data from books, movies, and sports.

## 👥 Contributors

- Shuan Zhou
- Cedric Lim
- Maggie Cheung
- Johannes Sulton

> Project Group: G18

---

## 🧠 Project Features

- **NERC (Named Entity Recognition & Classification)** using Conditional Random Fields (CRF)
- **Sentiment Analysis** using both Logistic Regression and BERT
- **Topic Classification** using ELECTRA fine-tuned on domain-specific datasets

---

## 📁 Datasets Used

The project utilizes publicly available datasets across different domains:

1. 📚 **Books**  
   [Amazon Kindle Book Reviews](https://www.kaggle.com/datasets/meetnagadia/amazon-kindle-book-review-for-sentiment-analysis)

2. 🎬 **Movies**  
   [IMDB Movie Reviews with Ratings (50k)](https://www.kaggle.com/datasets/nisargchodavadiya/imdb-movie-reviews-with-ratings-50k?select=imdb_sup.csv)

3. ⚽ **Sports**  
   [FIFA World Cup 2022 Tweets](https://www.kaggle.com/datasets/tirendazacademy/fifa-world-cup-2022-tweets)

---

## 🧪 Models & Techniques

| Task              | Model(s) Used (Fine-Tuned)             |
|-------------------|----------------------------------------|
| NERC              | Conditional Random Fields (CRF)        |
| Sentiment Analysis| Logistic Regression, BERT              |
| Topic Analysis    | ELECTRA                  |

---

## 📊 Evaluation Metrics

The models were evaluated using the following metrics:
- **Accuracy**
- **Precision**
- **Recall**
- **F1 Score**
- **Macro Average**
- **Weighted Average**

These metrics were computed for both development and unseen test sets to ensure robust evaluation.

---

## 🖥️ Setup & Usage

### 🔧 Environment
- Local Python environment (tested on Python 3.10+)

### 📦 Dependencies
Install required packages via cells in individual Jupyter Notebook

---

## 🙌 Acknowledgements

This project was developed as part of a collaborative group effort.  
We would like to thank:

- The authors and curators of the Kaggle datasets used in this project  
- The developers of open-source libraries including:
  - [Hugging Face Transformers](https://huggingface.co/transformers/)
  - [Scikit-learn](https://scikit-learn.org/)
  - [Pandas](https://pandas.pydata.org/)
  - and other NLP tooling that enabled our work
