# Customer Review Sentiment Classification

<p align="center">

**An NLP-Based Machine Learning Mini Project**

Classifying customer reviews into Positive and Negative sentiments using TF-IDF and Logistic Regression.

</p>

---

## Project Overview

Customer reviews contain valuable information about customer satisfaction, product quality, and service experience. Manually analyzing thousands of reviews can be time-consuming.

This project uses **Natural Language Processing (NLP)** and Machine Learning to automatically classify customer reviews into two sentiment categories:

- Positive
- Negative

The system processes review text, extracts meaningful numerical features using TF-IDF, and predicts sentiment using a Logistic Regression classifier.

## Objectives

- Understand Natural Language Processing concepts.
- Preprocess and clean customer review data.
- Apply TF-IDF for text feature extraction.
- Train a Logistic Regression classification model.
- Predict sentiment for new customer reviews.
- Evaluate the model using machine learning metrics.

## Technologies Used

| Technology | Purpose |
|---|---|
| Python | Programming language |
| Pandas | Dataset processing |
| Scikit-learn | Machine Learning |
| TF-IDF | Text feature extraction |
| Logistic Regression | Sentiment classification |
| Joblib | Model saving |
| Git and GitHub | Version control |

## Project Structure

```text
customer-review-sentiment/
│
├── data/
│   └── reviews.csv
│
├── docs/
│   └── Customer_Review_Sentiment_Project_Report.docx
│
├── src/
│   └── sentiment_classifier.py
│
├── README.md
├── requirements.txt
└── .gitignore
```

## Dataset Description

The dataset contains customer reviews and their sentiment labels.

| Column | Description |
|---|---|
| review_text | Customer review |
| sentiment | Positive or negative |

**Current sample dataset:** 20 illustrative records.

- Positive reviews: 10
- Negative reviews: 10

*Note: This small dataset is intended for demonstration and code testing. It is not suitable for claiming general model performance.*

## System Workflow

```text
Customer Reviews
       |
       v
 Dataset Loading
       |
       v
 Data Cleaning
       |
       v
 Text Preprocessing
       |
       v
 TF-IDF Vectorization
       |
       v
 Logistic Regression
       |
       v
 Sentiment Prediction
       |
       v
 Positive / Negative
```

## Installation and Setup

### 1. Clone the repository

```bash
git clone https://github.com/YOUR-USERNAME/customer-review-sentiment.git
```

### 2. Open the project folder

```bash
cd customer-review-sentiment
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Prepare the dataset

Copy `data/reviews.csv` into the project root folder.

Windows PowerShell:

```powershell
Copy-Item .\data\reviews.csv .\reviews.csv
```

### 5. Run the project

```bash
python src/sentiment_classifier.py
```

## Model Evaluation

The model evaluates predictions using:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

Actual performance values should be generated using a sufficiently large, properly sourced and labelled dataset.

## Output Files

After execution, the program generates:

```text
sentiment_model.joblib
sentiment_predictions.csv
```

- `sentiment_model.joblib`: Saved trained machine learning pipeline.
- `sentiment_predictions.csv`: Actual and predicted sentiment labels.

## Future Enhancements

- Add neutral sentiment classification.
- Compare Naive Bayes, SVM and Logistic Regression.
- Implement LSTM and Transformer-based models.
- Develop a web-based sentiment analysis dashboard.
- Support multilingual customer reviews.
- Perform aspect-based sentiment analysis.

## Academic Information

**Project Title:** Customer Review Sentiment Classification

**Student:** Kumar Keshav

**UID:** 25MCI10263

**Programme:** Master of Computer Applications (AI & ML)

**University:** Chandigarh University

**Project Supervisor:** Ms. Manisha Nagpal

## Author

**Kumar Keshav**

MCA (AI & ML) Student | AI/ML Enthusiast

---

*This project is developed for academic and educational purposes.*

