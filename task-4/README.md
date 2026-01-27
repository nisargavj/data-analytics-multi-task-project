# TASK-4: Sentiment Analysis Using NLP

## 📌 Objective
To perform sentiment analysis on textual data (such as tweets or reviews) using Natural Language Processing (NLP) techniques and machine learning models, and to classify text into positive or negative sentiments.

---

## 📊 Dataset
The dataset contains textual data with sentiment labels.

**Typical Columns:**
- `text` – User review or tweet
- `sentiment` – Sentiment label (0 = Negative, 1 = Positive)

The dataset is used only for NLP-based sentiment analysis.

---

## 🛠 Tools & Technologies Used
- Python
- Jupyter Notebook
- Pandas
- NumPy
- NLTK
- Scikit-learn
- Matplotlib / Seaborn

---

## 🔄 Steps Performed

### 1. Data Loading
- Imported dataset using Pandas
- Checked for missing values and data structure

### 2. Text Preprocessing
- Converted text to lowercase
- Removed special characters and numbers
- Removed stopwords
- Applied stemming
- Created a cleaned text column

### 3. Feature Extraction
- Converted text data into numerical format using **TF-IDF Vectorizer**

### 4. Model Building
- Split data into training and testing sets
- Trained a **Logistic Regression** model for sentiment classification

### 5. Model Evaluation
- Evaluated model using:
  - Accuracy score
  - Classification report
  - Confusion matrix

### 6. Prediction
- Tested the model with custom user input text to predict sentiment

---

## 📈 Key Insights
- Text preprocessing significantly improves model performance.
- TF-IDF effectively converts text into meaningful numerical features.
- Logistic Regression performs well for binary sentiment classification.
- The model can accurately predict sentiment for unseen text data.

---

## 📁 Project Structure

---

## ✅ Outcome
A complete sentiment analysis pipeline demonstrating data preprocessing, feature extraction, model training, evaluation, and sentiment prediction using NLP techniques.
## 📌 Note
This task uses a **text-based dataset**, which is different from numerical datasets used in other tasks, as sentiment analysis specifically requires textual data.
