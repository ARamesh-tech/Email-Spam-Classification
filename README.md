# 📧 Email / SMS Spam Classification

A Machine Learning-based web application that classifies messages as
**Spam** or **Not Spam** using Natural Language Processing (NLP)
techniques and a trained model deployed via Streamlit.

------------------------------------------------------------------------

## 🚀 Live Demo

👉 Check the app working in Streamlit Cloud:\
🔗
https://email-spam-classification-aramesh-kumaran-22mic0072.streamlit.app/

------------------------------------------------------------------------

## 📌 Features

-   Classifies email/SMS messages as **Spam** or **Not Spam**
-   Uses **TF-IDF Vectorization** for feature extraction
-   Implements **Multinomial Naive Bayes** for classification
-   Interactive UI built using **Streamlit**
-   Text preprocessing using:
    -   Lowercasing
    -   Tokenization
    -   Stopword removal
    -   Stemming

------------------------------------------------------------------------

## 🧠 Tech Stack

-   **Python**
-   **Scikit-learn**
-   **NLTK**
-   **Streamlit**
-   **Pickle**

------------------------------------------------------------------------

## 📂 Project Structure

    Email-Spam-Classification/
    │
    ├── app.py                # Streamlit app
    ├── model.pkl            # Trained ML model
    ├── vectorizer.pkl       # TF-IDF vectorizer
    ├── requirements.txt     # Dependencies
    └── README.md            # Project documentation

------------------------------------------------------------------------

## ⚙️ Installation & Setup

### 1️⃣ Clone the repository

    git clone https://github.com/ARamesh-tech/Email-Spam-Classification.git
    cd Email-Spam-Classification

### 2️⃣ Install dependencies

    pip install -r requirements.txt

### 3️⃣ Download NLTK data

    import nltk
    nltk.download('punkt')
    nltk.download('punkt_tab')
    nltk.download('stopwords')

### 4️⃣ Run the app

    streamlit run app.py

------------------------------------------------------------------------

## 🧪 How It Works

1.  User inputs a message\
2.  Text is preprocessed:
    -   Tokenized
    -   Stopwords removed
    -   Stemmed\
3.  Converted into numerical features using **TF-IDF**\
4.  Passed to trained **Naive Bayes model**\
5.  Output displayed as:
    -   🚫 Spam\
    -   ✅ Not Spam

------------------------------------------------------------------------

## 📊 Model Details

-   Algorithm: **Multinomial Naive Bayes**
-   Vectorizer: **TF-IDF**
-   Dataset: SMS Spam Dataset
-   Evaluation Metrics:
    -   Accuracy
    -   Precision

------------------------------------------------------------------------

## 🔥 Future Improvements

-   Add more ML models (Logistic Regression, SVM)
-   Improve UI/UX
-   Add model comparison dashboard
-   Deploy using Docker / CI-CD
-   Replace NLTK with faster preprocessing (for production)

------------------------------------------------------------------------

## 👨‍💻 Author

**A Ramesh**\
GitHub: https://github.com/ARamesh-tech

------------------------------------------------------------------------

## ⭐ If you like this project

Give it a ⭐ on GitHub and share it!
