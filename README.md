
# 🍷 Wine Classification Project

This project focuses on classifying different types of wines using various machine learning models. It aims to analyze physicochemical properties of **red** and **white** wine samples and predict wine quality effectively. The implementation and analysis are done in a Jupyter Notebook.

---

## 📁 Files Included

| File Name               | Description |
|------------------------|-------------|
| `red_wine_data.csv`     | Dataset containing features of red wines |
| `white_wine_data.csv`   | Dataset containing features of white wines |
| `wine_merged_dataset.csv` | Combined dataset of red and white wines with an additional column indicating wine type |
| `Wine_Classification.ipynb` | Jupyter Notebook containing preprocessing, model training, evaluation, and results |

---

## 📊 Dataset Information

The datasets were obtained from the UCI Machine Learning Repository and include the following features:

- **Fixed Acidity**
- **Volatile Acidity**
- **Citric Acid**
- **Residual Sugar**
- **Chlorides**
- **Free Sulfur Dioxide**
- **Total Sulfur Dioxide**
- **Density**
- **pH**
- **Sulphates**
- **Alcohol**
- **Quality** (Target variable)

Additional column in merged dataset:
- **Type**: Red or White wine

---

## ⚙️ Project Workflow

1. **Data Loading and Preprocessing**
   - Merge datasets
   - Encode wine types
   - Handle missing values
   - Feature scaling

2. **Exploratory Data Analysis (EDA)**
   - Visualization of feature distributions
   - Correlation heatmaps

3. **Model Building**
   - **Decision Tree Classifier**
   - **Gaussian Naïve Bayes**
   - Train-test split
   - Model evaluation (accuracy, classification report)

4. **Comparison and Insights**
   - Model performance comparison
   - Feature importance analysis

---

## 🧪 Dependencies

Make sure to install the following Python libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

---

## 📈 Results Summary

The project compares different classification models and identifies the most accurate and interpretable approach for wine quality prediction. Detailed evaluation metrics and plots are available in the Jupyter Notebook.

---

## 🧠 Key Takeaways

- Decision Trees provide better interpretability but may overfit.
- Naïve Bayes offers simplicity and speed but might struggle with feature independence assumptions.
- Feature scaling and EDA play a crucial role in improving performance and understanding the data.

---

## 📜 License

This project is for academic and educational use only. Feel free to use or adapt it with proper credit.

---

## 👤 Author

**Haveela Gadde**  
MSc Data Science   
