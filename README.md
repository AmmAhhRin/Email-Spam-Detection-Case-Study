# Email Spam Detection Case Study

This project presents a comparison between **Naive Bayes (NB)** and **Support Vector Machine (SVM)** algorithms for email spam detection using a real-world dataset of email messages. The objective is to build classifiers that can accurately differentiate between **spam** and **non-spam** emails.

---

## Overview

Spam emails account for a significant portion of global email traffic and pose threats ranging from data breaches to user inconvenience. This study uses machine learning to automate spam detection, improving email security and user experience.

Two classification models were developed and compared:
- **Naive Bayes**: Known for its efficiency and performance in text classification.
- **Support Vector Machine**: Offers high accuracy and works well in high-dimensional spaces.

---

## Files Included

- `Email_Spam(SVM_&_NB).ipynb` – Main Jupyter Notebook containing the code for data loading, preprocessing, training, and evaluation.
- `Email Spam Detection Case Study.pdf` – Slide presentation explaining the background, methodology, results, and key takeaways.

---

## ⚙️ How to Run

1. Clone the repo or download the notebook file.
2. Make sure you have Python installed with the following packages:
   ```bash
   pip install numpy pandas scikit-learn matplotlib seaborn
   ```
3. Open the Jupyter Notebook:
   ```bash
   jupyter notebook Email_Spam(SVM_&_NB).ipynb
   ```
4. Run the cells to:
   - Load and explore the data
   - Preprocess the text
   - Train Naive Bayes and SVM models
   - Evaluate model performance

---

## Output & Evaluation

- Models are evaluated using metrics such as **accuracy**, **precision**, **recall**, and **F1-score**.
- Confusion matrices and classification reports are displayed to show comparative performance.
- SVM generally provides **higher accuracy**, while Naive Bayes is **faster and simpler** to implement.

---

## Key Insights

- **Naive Bayes** is lightweight, fast, and surprisingly effective for spam filtering.
- **SVM** offers robust performance, especially on complex datasets.
- The trade-off is between **speed** (Naive Bayes) and **accuracy** (SVM).

---

## Applications

- Email clients (e.g., Gmail, Outlook)
- Messaging apps and services
- Enterprise mail filtering systems

---

## 🧾 References
See the `Email Spam Detection Case Study.pdf` for a detailed list of sources and image credits.

---
If there are inquiries regarding the dashboard, please contact:

Email: somphorsyun24@gmail.com
LinkedIn: www.linkedin.com/in/somphorsyun
