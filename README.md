# 📧 Spam Classifier

A machine learning–based **Spam Message Classifier** that predicts whether a given message is **Spam** or **Not Spam (Ham)**. This project uses Natural Language Processing (NLP) techniques and a supervised learning model trained on labeled text data.

---

## 🚀 Features

* Text preprocessing (cleaning, stopword removal, stemming)
* Vectorization using Bag of Words / TF-IDF
* Trained classification model (Naive Bayes)
* Fast and lightweight prediction
* Easy to extend or deploy

---

## 🛠️ Tech Stack

* **Language:** Python
* **Libraries:**

  * pandas
  * numpy
  * scikit-learn
  * nltk
  * pickle

---

## 📂 Project Structure

```
spam-classifier/
│
├── data/                 # Dataset files (CSV)
├── notebook/             # Jupyter notebook for training
├── model.pkl             # Trained ML model
├── vectorizer.pkl        # Saved vectorizer
├── app.py / main.py      # Prediction script
├── requirements.txt      # Dependencies
└── README.md             # Project documentation
```

---

## 📊 Dataset

The dataset consists of labeled SMS/email messages with two classes:

* **Spam** – Unwanted or promotional messages
* **Ham** – Legitimate messages

Example:

```
Label | Message
spam  | Congratulations! You won a prize
ham   | Are we meeting tomorrow?
```

---

## ⚙️ How It Works

1. Text data is cleaned and preprocessed
2. Messages are converted into numerical vectors
3. A Naive Bayes classifier is trained
4. The trained model is saved using `pickle`
5. New messages are classified using the saved model

---

## ▶️ Installation & Usage

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/spam-classifier.git
cd spam-classifier
```

### 2️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

### 3️⃣ Run Prediction

```bash
python main.py
```

---

## 🧪 Sample Output

```
Enter your message: Win a free iPhone now!
Prediction: Spam
```

---

## 📌 Future Improvements

* Use advanced models (Logistic Regression, SVM)
* Deploy using Flask or Streamlit
* Add web UI
* Improve accuracy with lemmatization

---

## 🤝 Contributing

Contributions are welcome! Feel free to fork this repo and submit a pull request.

---

## 📜 License

This project is licensed under the **MIT License**.

---

## 👨‍💻 Author

**Abhay Shroti**
Engineering Student | Machine Learning Enthusiast
