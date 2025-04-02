#  Alzheimer's Disease Risk Prediction using Machine Learning

This project uses supervised machine learning models to predict the risk of Alzheimer's disease based on a real-world clinical dataset. It explores and compares different classification algorithms, performs extensive preprocessing, and applies ensemble learning for performance improvement.

---

##  Project Structure

- `Chapagain_AMLHW2.ipynb` – The Jupyter notebook containing full data analysis, model training, hyperparameter tuning, and evaluations.
- `annotated-Chapagain_AMLHW2.pdf` – A polished report with code, explanations, and results in PDF format.
- `README.md` – Project overview and usage guide.

---

##  Dataset

The dataset is sourced from the [Kaggle Alzheimer’s Disease Risk Prediction – EU Business](https://www.kaggle.com/competitions/alzheimers-disease-risk-prediction-eu-business) competition.

It contains demographic, medical, lifestyle, and cognitive test attributes for over 1,700 patients.

---

## 🛠 Models Used

- **Logistic Regression (Multinomial / Softmax)**
- **Support Vector Machine (SVM)**
- **Random Forest Classifier**
- **Voting Ensembles (Hard and Soft Voting)**

Hyperparameter tuning was done manually and via grid search to optimize model performance.

---

##  Evaluation Metrics

Each model is evaluated using:
- Accuracy
- Precision
- Recall
- F1 Score
- Classification reports on training, validation, and test sets

The ensemble models outperformed individual classifiers in terms of generalization and stability.

---

##  Key Insights

- Functional and cognitive test features (e.g., ADL, MMSE) had the highest predictive value.
- The soft voting ensemble achieved the best overall performance (Test Accuracy ~87.6%).
- Feature importance analysis confirmed medical relevance of the top predictors.

---

##  Getting Started

To run the notebook:

1. Clone this repo:
    ```bash
    git clone https://github.com/Biophylo2001/-Alzheimer-s-Disease-Risk-Prediction.git
    ```
2. Open `Chapagain_AMLHW2.ipynb` in Jupyter Notebook or VSCode.
3. Install required packages:
    ```bash
    pip install pandas numpy matplotlib seaborn scikit-learn
    ```
4. Run the cells to explore the workflow.

---

##  License

This project is shared for educational purposes. Please cite the original Kaggle dataset and creator if you reuse the data or methodology.

---

##  Author

**Sanyukta Chapagain**  
Graduate Student, Bioinformatics  
GitHub: [Biophylo2001](https://github.com/Biophylo2001)

