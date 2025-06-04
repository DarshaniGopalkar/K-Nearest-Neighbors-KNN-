🌸 Iris Flower Classification — K-Nearest Neighbors (KNN)
This project is part of an AI & ML Internship, focused on implementing K-Nearest Neighbors (KNN) for multi-class classification using the Iris dataset.

📄 Objective
To build and evaluate a KNN classification model to predict the species of iris flowers based on their sepal and petal dimensions.

📋 Steps:
1. Loaded the dataset (Iris.csv) using Pandas
2. Dropped the unnecessary column (Id)
3. Split the data into features (X) and target (y)
4. Normalized the features using StandardScaler
5. Performed train-test split (80% training, 20% testing)
6. Trained a KNN Classifier (K = 5) using KNeighborsClassifier
7. Predicted test results and calculated accuracy
8. Evaluated model using confusion matrix and classification report
9. Tested multiple values of K (1 to 20)
10. Plotted Accuracy vs. K to choose the optimal value
11. Interpreted results and selected the best-performing K

📊 Results:
Model Accuracy (K=5): ~97%
Best Accuracy: Achieved at K = 5
Confusion Matrix: Almost perfect classification across the 3 flower species
Accuracy vs. K plot: Helped visualize the performance trend for various K values

🛠 Tools Used
Python
Pandas, NumPy
Matplotlib, Seaborn
Scikit-learn (KNeighborsClassifier, StandardScaler, train_test_split, accuracy_score, etc.)

✅ Files
Iris.csv – Iris flower dataset
Task_06_KNN.ipynb – Jupyter notebook with code and analysis
README.md – Project summary
