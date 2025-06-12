# 📰 Fake News Detection Using LSTM

This project uses **Long Short-Term Memory (LSTM)**, a type of Recurrent Neural Network (RNN), to accurately detect and classify fake and real news articles based on their textual content.

---

## 📚 Dataset

- **Source**: [Fake and Real News Dataset on Kaggle](https://www.kaggle.com/datasets/clmentbisaillon/fake-and-real-news-dataset)
- Contains labeled news articles with binary classification: `FAKE` or `REAL`
- Preprocessing includes:
  - Lowercasing
  - Removing punctuation and stopwords
  - Tokenization and padding for LSTM input

---

## 🧠 Model Architecture

- **LSTM-based neural network**
- Embedding layer for word vector representation
- One or more LSTM layers followed by dense layers
- Binary classification output (Real or Fake)

---

## 📊 Performance

- ✅ **Accuracy**: **97.9%**
- Model shows strong performance on both training and validation sets
- Can be extended to multi-class classification or real-time news feeds

---

## 🛠 Tech Stack

- Python 3.x  
- TensorFlow / Keras  
- Pandas, NumPy  
- Matplotlib & Seaborn (for visualization)  
- Scikit-learn (for preprocessing & evaluation)

---

## 🚀 How to Run

1. Clone this repository  
2. Install the required libraries using `pip install -r requirements.txt`  
3. Run the notebook or script to train the model

---

## 📬 Contact

For questions or collaboration:  
📧 **luckyjoytutika@gmail.com**

---

## 🧾 License

This project is intended for educational and research use only.

