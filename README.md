🚀 Credit Card Fraud Detection – Pattern Recognition Project
This is my first project in the Pattern Recognition course at the Egyptian E-Learning University.
The project focuses on detecting fraudulent credit card transactions using Machine Learning techniques applied on a real-world dataset.
The dataset is highly imbalanced, which makes the problem more challenging and closer to real-life financial fraud detection scenarios.


📊 Dataset
The dataset used in this project is taken from Kaggle:

Credit Card Fraud Detection Dataset (Kaggle)
https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

It contains 284,807 transactions, where only 492 are fraud cases (0.17%).
This makes it a highly imbalanced classification problem.


🧠 Models Used
In this project, I implemented and compared multiple machine learning models:
Logistic Regression
Decision Tree
Random Forest


📌 Evaluation Metrics
Due to the imbalance in the dataset, accuracy alone was not enough.
So I focused on:
Precision
Recall
F1-score


🔍 Key Insights
Fraud transactions are very rare compared to normal ones
Most features (V1 to V28) are PCA-transformed
Some features such as V14, V4, and V12 showed stronger influence on fraud detection
Data preprocessing included scaling, cleaning, and removing duplicates


🏆 Results
Random Forest achieved the best overall performance
Better detection of fraud cases compared to other models
Good balance between Precision and Recall


💡 Conclusion
This project helped me understand how machine learning is applied to real-world financial problems, especially dealing with imbalanced datasets and selecting the right evaluation metrics instead of relying only on accuracy.


🛠️ Tools & Libraries
Python
Pandas
NumPy
Scikit-learn
Matplotlib
Jupyter Notebook


📌 Author
Student at Egyptian E-Learning University
Faculty of Computers – Artificial Intelligence Track
