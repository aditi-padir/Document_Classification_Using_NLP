# Document Classification Using NLP and Machine Learning

## 📌 Project Overview

This project focuses on building a **Document Classification System using Natural Language Processing (NLP) and Machine Learning**. It automatically classifies text documents into one of 20 different categories using the 20 Newsgroups dataset.

The project uses text preprocessing, TF-IDF feature extraction, and machine learning algorithms to understand document content and predict its category.

## 🎯 Objectives

- To understand and process unstructured text data.
- To perform text preprocessing using NLP techniques.
- To convert text into numerical features using TF-IDF.
- To train and compare different machine learning models.
- To classify new documents into appropriate categories.

## 📂 Dataset

**20 Newsgroups Dataset**

- Contains documents belonging to 20 different newsgroup categories.
- Used for multi-class text classification.
- Loaded using Scikit-learn's `fetch_20newsgroups()` function.

## 🛠️ Technologies Used

- Python
- Natural Language Processing (NLP)
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Joblib
- Jupyter Notebook

## ⚙️ Project Workflow

1. **Data Collection:** Load the 20 Newsgroups dataset.
2. **Data Exploration:** Analyze document categories and dataset distribution.
3. **Text Preprocessing:** Convert text to lowercase and remove URLs, email addresses, punctuation, and extra spaces.
4. **Data Splitting:** Split the dataset into 80% training and 20% testing data.
5. **Feature Extraction:** Apply TF-IDF Vectorization to convert text into numerical features.
6. **Model Training:** Train three machine learning algorithms:
   - Multinomial Naive Bayes
   - Logistic Regression
   - Linear Support Vector Machine (Linear SVM)
7. **Model Evaluation:** Compare models using accuracy, precision, recall, F1-score, and confusion matrix.
8. **Prediction:** Predict categories of new text documents.

## 📊 Model Performance

| Machine Learning Model  | Accuracy |
| ----------------------- | -------: |
| Linear SVM              |   76.60% |
| Logistic Regression     |   74.80% |
| Multinomial Naive Bayes |   72.94% |

**Best Performing Model:** Linear Support Vector Machine (Linear SVM)

**Test Accuracy:** 76.60%

## 📁 Project Structure

```text
Document_Classification/
│
├── Document_Classification.ipynb
│
├── Models/
│   ├── best_document_classifier.pkl
│   ├── tfidf_vectorizer.pkl
│   └── category_names.pkl
│
└── README.md
```

## 🚀 How to Run the Project

1. Clone this repository:

```bash
git clone YOUR_GITHUB_REPOSITORY_LINK
```

2. Navigate to the project folder.

3. Install the required libraries:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn joblib
```

4. Open Jupyter Notebook:

```bash
jupyter notebook
```

5. Open `Document_Classification.ipynb`.

6. Run all cells to execute the complete project.

**Note:** The 20 Newsgroups dataset is downloaded through Scikit-learn when it is not already available locally.

## 🔍 Sample Prediction

The trained model can classify new documents automatically.

Example:

**Input:** NASA scientists are studying a new space telescope and distant planets.

**Predicted Category:** `sci.space`

## 📌 Key Learnings

- Understanding NLP fundamentals.
- Text cleaning and preprocessing.
- TF-IDF feature extraction.
- Multi-class text classification.
- Training and comparing machine learning algorithms.
- Model evaluation and performance analysis.
- Saving and reusing trained ML models.

## 🏁 Conclusion

This project demonstrates how NLP and machine learning can be used to automatically organize and classify text documents. Among the three algorithms, Linear SVM achieved the highest test accuracy of 76.60%.

The project helped develop practical knowledge of text preprocessing, feature extraction, machine learning model training, and document classification.

## 👩‍💻 Author

**Aditi Padir**

Artificial Intelligence and Data Science Student

