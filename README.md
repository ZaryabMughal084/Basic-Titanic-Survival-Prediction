## 🚢 Titanic Survival Prediction

This is my first Machine Learning project where I built a model to predict whether a passenger on the Titanic would survive or not.

## 🛠 Tools Used
==> **Python** (Core Logic)
==> **Pandas** (Data Cleaning & Preprocessing)
==> **Scikit-Learn** (Model Building)

 📊 Project Steps
1.  **Data Cleaning:** Handled missing values in `Age` and `Embarked` columns.
2.  **Preprocessing:** Converted categorical data (`Sex`, `Embarked`) into numerical format for the model.
3.  **Feature Selection:** Removed irrelevant columns like `Name`, `Ticket`, and `Cabin` to improve model focus.
4.  **Modeling:** Used **Decision Tree Classifier** to train the model.

## 📈 Results
--> The model achieved an accuracy of **~75.8%** on the test dataset.
--> This demonstrates that simple demographic factors (Age, Gender, Class) were strong indicators of survival.

## 🚀 Future Improvements
--> Plan to test Random Forest algorithm to improve accuracy.
--> Will analyze `Fare` and `FamilySize` correlations deeply.
