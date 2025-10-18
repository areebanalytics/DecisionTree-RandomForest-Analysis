# DecisionTree-RandomForest-Analysis
This project focuses on predicting whether an individual earns more than $50K per year using the Census Income dataset (also known as the Adult dataset). The project applies Decision Tree and Random Forest algorithms to classify income levels based on demographic and work-related features.

🧠 Objective

To build and compare two supervised machine learning models — Decision Tree and Random Forest — for accurate income prediction.

🧾 Dataset

Source: Census Income Dataset

The dataset includes attributes such as age, education, occupation, hours-per-week, and income category.

🧰 Libraries Used

pandas – Data loading and preprocessing

numpy – Numerical operations

matplotlib – Data visualization

sklearn.tree – Decision Tree Classifier

sklearn.ensemble – Random Forest Classifier

sklearn.metrics – Model evaluation using classification report

⚙️ Steps Involved

Data Cleaning – Removed missing or inconsistent values.

Encoding – Converted categorical variables using pd.get_dummies().

Model Training – Trained both Decision Tree and Random Forest classifiers.

Evaluation – Compared models using accuracy, precision, recall, and F1-score.

Visualization – Displayed decision boundaries and feature importance.

📈 Results

Both models achieved high accuracy on the test data.

Random Forest outperformed the Decision Tree model with better generalization and stability.

💡 Conclusion

Tree-based models are effective for income prediction tasks. Random Forest, due to its ensemble nature, provides more reliable predictions and reduces overfitting compared to a single Decision Tree.

https://colab.research.google.com/drive/1uIp75Po_opQsFBHaXoWUYKBGZGv52phg?usp=drive_link
