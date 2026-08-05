# Deep_Learning
# Bangla Cybercrime Complaint Classification

## 🎥 Deployment Demo

Watch the deployment video first to understand how the system works.

**Deployment Video:**
*👉 Add your video link here*

---

## 📌 Project Overview

This project focuses on the automatic classification of **Bangla cybercrime complaints** using Machine Learning, Deep Learning, and Transformer-based models. The system classifies a user's complaint into the appropriate cybercrime category, helping automate the complaint analysis process.

The project compares the performance of five different models:

* BiLSTM
* BanglaBERT
* XLM-R
* BERT
* Naive Bayes

---

## ✨ Features

* Bangla cybercrime complaint classification
* Automatic text preprocessing
* Prediction using trained classification models
* User-friendly interface
* Comparative performance analysis

---

## 🗂 Dataset

* **Language:** Bangla
* **Dataset Size:** 1,500 manually annotated cybercrime complaints
* **Task:** Multi-class text classification

---

## ⚙️ Data Preprocessing

The following preprocessing steps were applied before training:

* Text cleaning
* Removal of unnecessary symbols and punctuation
* Duplicate record removal
* Text normalization
* Tokenization
* Train, Validation, and Test split

---

## 🤖 Models Used

1. Naive Bayes
2. BiLSTM
3. BERT
4. BanglaBERT
5. XLM-R

---

## 📊 Experimental Results

| Model       |   Accuracy | Precision |    Recall |  F1-score |
| ----------- | ---------: | --------: | --------: | --------: |
| **BiLSTM**  | **89.00%** | **84.2%** | **80.0%** | **81.0%** |
| BanglaBERT  |     85.78% |     78.0% |     73.0% |     80.0% |
| XLM-R       |     85.55% |     79.0% |     71.0% |     81.0% |
| Naive Bayes |     75.00% |     71.0% |     69.0% |     70.0% |
| BERT        |     67.00% |     65.0% |     69.1% |     66.0% |

---

## 🛠 Technologies Used

* Python
* Google Colab
* PyTorch
* Hugging Face Transformers
* BanglaBERT
* XLM-R
* BERT
* Scikit-learn
* Pandas
* NumPy

---

## 📁 Project Structure

```text
├── Dataset/
├── Models/
├── Notebook/
├── Deployment/
├── README.md
└── requirements.txt
```

---

## 🚀 How to Run

1. Clone the repository.
2. Install the required packages.

```bash
pip install -r requirements.txt
```

3. Run the training notebook or load the trained model.
4. Launch the deployment application.
5. Enter a Bangla cybercrime complaint and obtain the predicted category.

---

## 📌 Conclusion

Among all the evaluated models, **BiLSTM** achieved the highest performance with an accuracy of **89%**. The results indicate that BiLSTM is the most effective model for Bangla cybercrime complaint classification, while BanglaBERT and XLM-R also demonstrated strong performance.

---

## 👩‍💻 Authors

* Fabiha Bushra Chowdhury


---

## 📄 License

This project is intended for academic and research purposes.
