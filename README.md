# Student Exam Data - Logistic Regression Classification

This project implements a **Logistic Regression** model using Python to predict whether a student will **Pass** or **Fail** based on their daily study hours and school attendance percentage. It serves as a practical implementation of machine learning classification concepts, complete with data visualization.

## 📊 Key Features & Workflow
1. **Data Preprocessing & Encoding:** Converted categorical target labels (`Pass`/`Fail`) into binary format (`1` and `0`) using Pandas.
2. **Data Splitting:** Divided the dataset into an 80% training set and a 20% testing set using `train_test_split`.
3. **Model Training:** Built and trained a `LogisticRegression` model from `scikit-learn`.
4. **Data Visualization:**
   * Created a **Count Plot** to analyze the distribution of passing and failing students.
   * Plotted a **Decision Boundary** line on a scatter plot to visually demonstrate how the trained model separates the classification groups.
5. **Robust Testing:** Implemented sample prediction input handled as a Pandas DataFrame to maintain strict consistency with feature names and avoid formatting warnings.

## 🛠️ Technologies Used
* **Language:** Python
* **Libraries:** Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
* **Environment:** Jupyter Notebook

## 📈 Model Performance
* **Accuracy:** 66.67% (Tested on a standard stratified random split)
