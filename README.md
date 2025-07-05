# Titanic_ml
# Titanic - Machine Learning from Disaster 🚢

This is my **first machine learning project**, built using the Titanic dataset from Kaggle. It predicts whether a passenger survived or not based on features like age, gender, ticket class, and fare.

---

## 📚 What I Learned

- Basic data cleaning and preprocessing with Pandas
- Data visualization using Seaborn and Matplotlib
- Encoding categorical variables with `pd.get_dummies()`
- Handling missing values safely (no `inplace=True` warnings!)
- Training a machine learning model (Logistic Regression)
- Evaluating model performance using accuracy and confusion matrix
- Making predictions and generating a Kaggle submission file

---


## ⚙️ How It Works

1. Load and explore the dataset
2. Clean and fill missing values (`Age`, `Fare`, `Embarked`)
3. Convert categorical features (`Sex`, `Embarked`) using one-hot encoding
4. Train a Logistic Regression model
5. Evaluate predictions using test data
6. Generate `submission.csv` for Kaggle

---

## 🛠 Technologies Used

- Python 3
- Jupyter Notebooks (in VS Code)
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

---

## 📈 Output Example

```python
sns.countplot(x=predictions)
