# Student Marks Prediction Using Machine Learning

## 📌 Project Overview

This project predicts students' final exam marks using **Machine Learning (Linear Regression)**. It uses the **Student Performance Dataset** from the UCI Machine Learning Repository.

## 🎯 Objective

To predict students' final grades based on study time, absences, and previous examination grades.

## 🛠️ Technologies Used

- Python
- Pandas
- Scikit-learn
- Matplotlib
- UCI ML Repository (`ucimlrepo`)
- Jupyter Notebook

## 📊 Dataset

**Source:** [UCI Student Performance Dataset](https://archive.ics.uci.edu/dataset/320/student+performance)

**Input Features:**

- `studytime` – Weekly study time category (1–4)
- `absences` – Number of school absences
- `G1` – First-period grade
- `G2` – Second-period grade

**Target Variable:**

- `G3` – Final grade (0–20)

## 🤖 Machine Learning Algorithm

**Linear Regression** is used to predict students' final marks based on their academic information.

## ⚙️ Installation

Install the required libraries:

```bash
pip install pandas scikit-learn matplotlib ucimlrepo
```

## 🚀 How to Run

1. Clone or download this repository.
2. Open Jupyter Notebook.
3. Open `student_marks_prediction.ipynb`.
4. Run all cells sequentially.
5. View the predicted marks and evaluation results.

## 📈 Model Evaluation

The model is evaluated using:

- **MAE (Mean Absolute Error):** Measures average prediction error.
- **R² Score:** Measures how well the model explains variations in student marks.

## 📁 Project Structure

```text
Student-Marks-Prediction/
│
├── student_marks_prediction.ipynb
└── README.md
```

## ✅ Conclusion

This project demonstrates how Linear Regression can predict student academic performance using historical student data. It provides a simple introduction to supervised machine learning and regression techniques.

## 🔗 Submission Details

**Submission GitHub ID:** [https://github.com/complexiota](https://github.com/complexiota)

## 📚 Reference

[UCI Machine Learning Repository – Student Performance Dataset](https://archive.ics.uci.edu/dataset/320/student+performance)

## 📝 Note

This project is developed for educational purposes. Predictions are estimates and may not represent actual student performance.
