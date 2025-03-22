# Sentiment Analysis with NLP

*COMPANY* : CODTECH IT SOLUTIONS

*NAME* : PREETHAM B

*INTERN ID* : CT12WM72

*DOMAIN* : MACHINE LEARNING 

*DURATION* : 12 WEEKS

*MENTOR* : NEELA SANTOSH 

## Introduction

This project focuses on **Sentiment Analysis** of customer reviews using **Natural Language Processing (NLP)** techniques. The goal is to classify reviews as **positive (1)** or **negative (0)** based on textual data. We utilize **TF-IDF Vectorization** to convert text into numerical form and apply **Logistic Regression** for classification.

## Task Objective

### The primary objective of this task is to:

1. **Preprocess** customer review data.
2. **Vectorize** text data using TF-IDF.
3. **Train and evaluate** a Logistic Regression model for sentiment classification.
4. **Assess performance** using accuracy, precision, recall, and F1-score.
5. **Document** the entire process in a **Jupyter Notebook**.

## Dataset

The dataset consists of customer reviews(I've used Flipkart_Product reviews from kaggle) with attributes:
- **Review**: The actual customer feedback.
- **Rate**: The numerical rating (1 to 5).
- **Sentiment**: The derived sentiment label (**1 for positive, 0 for negative**).

## Methodology

### 1. Data Preprocessing

- Removed non-ASCII characters from reviews.
- Converted ratings into binary sentiment labels (ratings **>=3** as positive, **<3** as negative).
- Cleaned text by removing special characters, converting to lowercase, and eliminating stopwords.
- Tokenized and lemmatized words for better processing.

### 2. Text Vectorization (TF-IDF)

- **TF-IDF (Term Frequency-Inverse Document Frequency)** was applied to convert textual data into numerical form.
- This method assigns weights to words based on their importance in the dataset.

### 3. Model Training (Logistic Regression)

- Applied **Logistic Regression**, a supervised learning algorithm, for binary classification.
- Split the dataset into **training (80%) and testing (20%) sets**.

### 4. Model Evaluation

- **Accuracy Score**: 96.65%
- **Classification Report**:
  - Precision: 99% for negative, 96% for positive
  - Recall: 85% for negative, 100% for positive
  - F1-score: 92% for negative, 98% for positive
- **Confusion Matrix** to visualize correct vs incorrect classifications.

## Results

- The model performed exceptionally well, with an accuracy of **96.65%**.
- High precision and recall indicate strong performance in classifying sentiments.
- The **TF-IDF vectorization** effectively captured the importance of words, improving model accuracy.

## Deliverable

- A **Jupyter Notebook** containing:
  - Data preprocessing steps.
  - Text vectorization using TF-IDF.
  - Logistic Regression model training and evaluation.
  - Performance analysis with metrics.

## Future Improvements

- Implement **Deep Learning models** (LSTMs or Transformers) for better accuracy.
- Use **BERT embeddings** instead of TF-IDF for better word representation.
- Explore **other ML algorithms** like SVM or Random Forest.
- Add sentiment visualization (e.g., WordCloud, sentiment heatmaps).

## Conclusion

This project successfully performed **Sentiment Analysis** on customer reviews, achieving a high accuracy of **96.65%** using **TF-IDF** and **Logistic Regression**. The results demonstrate the effectiveness of NLP techniques in extracting valuable insights from textual data.

## Output

![Image](https://github.com/user-attachments/assets/e858d18c-c048-4324-9655-5aa51ec499ad)
![Image](https://github.com/user-attachments/assets/a2ba580a-4257-40c0-a8f4-213e27dbcfcb)



