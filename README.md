# Spam-Ham-Text-Classifier
98% Accurate Naive Bayes model for SMS Spam detection.
# 📧 SMS Spam/Ham Classifier

## 🚀 Project Overview

A concise and **highly accurate** Machine Learning solution built to automatically filter unwanted SMS messages (spam) from legitimate messages (ham). This project uses classic NLP techniques and the **Naive Bayes algorithm** to demonstrate text classification proficiency.

---

## 📊 Key Results

| Metric | Score |
| :--- | :--- |
| **Accuracy on Test Set** | **[ 98.39%]** |
| **Algorithm Used** | Multinomial Naive Bayes |

### Execution Proof

Attempting to load data...
Data loaded and cleaned successfully.
Data split: Training samples: 4457, Test samples: 1115
Model trained successfully.
--- Model Results ---
Accuracy on Test Set: [98.39]
Message: 'Hello, are we still meeting at the library tomorrow at 3 PM?'
Prediction: HAM (Legitimate) 👍
Message: 'URGENT! You have won a FREE £1000 prize! Text CLAIM to 80878 now to collect your reward.'
Prediction: SPAM 🚨
[Program finished]

## 🛠️ Technologies & Setup

### Requirements

To run this project locally, you need Python and the following libraries:

1.  `pandas`
2.  `scikit-learn`
3.  `numpy`

*(For easy installation, see the included `requirements.txt` file.)*

### How to Run

1.  **Clone the Repository:** Download the project files.
2.  **Dataset:** Ensure the **`spam.csv`** file is in the same folder as `spam_classifier.py`.
3.  **Execute:** Run the script using your Python interpreter:
    ```bash
    python spam_classifier.py
    ```

---

## 🎯 Future Roadmap

* Refine text features using **TF-IDF** (Term Frequency-Inverse Document Frequency).
* Explore deployment options by wrapping the model in a simple **Flask API endpoint**.

---

*Built by [ML-nerd-dev] | [25th Nov 2025]*
