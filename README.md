# SpamMessages

A machine learning-powered web app to classify SMS messages as **Spam** or **Not Spam**. Built with [Streamlit](https://streamlit.io/), [NLTK](https://www.nltk.org/), and [scikit-learn](https://scikit-learn.org/).

Try it online: [spammessages-drvss.streamlit.app](https://spammessages-drvss.streamlit.app/)

---

## 🚀 Features

- 🔎 Real-time SMS spam prediction
- ✂️ Text preprocessing (tokenization, stopword removal)
- 🤖 Machine learning model (MultinomialNB, TfidfVectorizer)
- 🌐 Simple, interactive UI via Streamlit

---

## 🏁 Getting Started

1. **Clone the repository:**
  git clone https://github.com/DRV-Sai-Siddarth/SpamMessages.git
  cd SpamMessages
2. **Install Python dependencies:**
   pip install -r requirements.txt
3. **Run the Streamlit app:**
   streamlit run app.py
---

## 🛠️ Technical Details

- **ML Model:** Trained using `scikit-learn` (MultinomialNB)
 - Vectorization via `TfidfVectorizer`
 - Model + vectorizer saved as `.joblib` files
- **Text Processing:** Leverages `NLTK` for tokenization & stopwords
- **Deployment:** Easily deployable to [Streamlit Cloud](https://streamlit.io/cloud)

**Important NLTK note:**  
If you deploy or run the app on a fresh environment, NLTK resources (`punkt_tab`, `punkt`, and `stopwords`) are downloaded at app startup for seamless operation.

---

## 📄 Project Structure

├── app.py # Main Streamlit app
├── requirements.txt # Python dependencies
├── spam_model.joblib # ML model weights
├── vectorizer.joblib # Fitted TF-IDF vectorizer
└── README.md # This file


---

## ⚙️ Requirements

- Python 3.7 or newer
- Packages in `requirements.txt`:
    - streamlit
    - scikit-learn
    - nltk
    - joblib

---

## 👨‍💻 Author

- **DRV Sai Siddarth**  
  [GitHub](https://github.com/DRV-Sai-Siddarth)

---

## 🙌 License

This project is open source. Feel free to use, modify, and share!

---

## 📝 Acknowledgments

- [NLTK](https://www.nltk.org/) for NLP tools and corpora
- [Streamlit](https://streamlit.io/) for rapid UI prototyping

---

**Happy Detecting!**

