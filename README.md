#  Predicting Medical Insurance Costs Using Machine Learning

This project uses machine learning models to predict medical insurance charges based on demographic and health-related features such as age, BMI, and smoking status.

##  Project Summary (PDF)

 [Click here to view the PDF summary](Predicting Medical Insurance Costs Using Machine Learning.pdf)

---

##  Dataset

- **Source**: [Kaggle – Medical Cost Personal Dataset](https://www.kaggle.com/datasets/mirichoi0218/insurance)
- **Size**: 1,338 records
- **Features**:
  - `age`, `sex`, `bmi`, `children`, `smoker`, `region`, `charges`

---

## Key Findings

- **Smokers** pay nearly **3x more** than non-smokers
- Charges increase with **age** and **BMI**
- Minimal cost difference by **region** or **gender**

---

##  Modeling Approach

| Model             | MAE  | RMSE | R² Score |
| ----------------- | ---- | ---- | -------- |
| Linear Regression | 4100 | 6100 | 0.79     |
| Random Forest     | 2700 | 4200 | 0.88     |

- Feature importance: **Smoker**, **Age**, **BMI**
- Random Forest outperformed Linear Regression in all metrics

---

##  Conclusion

- Lifestyle choices like **smoking** significantly influence insurance pricing
- ML models can be used for **transparent and fair pricing strategies**
- The project highlights how basic patient info can predict healthcare costs

---

##  Tools Used

- Python (Pandas, Seaborn, Matplotlib, Scikit-learn)
- Jupyter Notebook
- GitHub

---




## 🙌 Acknowledgments

- [Kaggle Dataset Author: Mirichoi0218](https://www.kaggle.com/datasets/mirichoi0218/insurance)

---

### 📌 Contact

Feel free to connect on [LinkedIn](https://www.linkedin.com/in/saubia-aimen-456a7321a/) or message for collaboration!
