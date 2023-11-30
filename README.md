# TechnoHacksintern-task3
In this project, I have developed a predictive model to identify customers who are likely to leave a company. By analyzing a dataset containing various customer attributes, I aimed to understand the factors contributing to customer churn and build a model to predict churn accurately. The model achieved an accuracy of 0.8097941802696949. 🎯✅

Here are the main steps I followed in this project:

1️⃣ First, I imported necessary libraries for data manipulation, visualization, and modeling.

2️⃣ The dataset was read into a pandas DataFrame to begin the analysis.

3️⃣ I conducted an initial exploration of the dataset, including examining the first few rows, dropping irrelevant columns such as 'customerID', and checking the data types.

4️⃣ Missing values in numerical columns, such as 'TotalCharges' and 'MonthlyCharges', were handled by appropriate methods.

5️⃣ Categorical variables in the dataset were encoded using the LabelEncoder to prepare them for the model.

6️⃣ I calculated the churn percentage and analyzed the columns that contribute the most to customer churn. Visualizations, including count plots and bar charts, helped to gain insights into churn patterns.

7️⃣ The dataset was split into training and testing sets using train_test_split from sklearn.model_selection.

8️⃣ Missing values in the training and testing sets were filled with appropriate methods.

9️⃣ Categorical variables were further encoded using one-hot encoding (get_dummies).

🔟 The Random Forest classifier was chosen as the model, and I performed hyperparameter tuning using GridSearchCV to find the best combination of parameters.

1️⃣1️⃣ The best model was identified from the grid search and used to make predictions on the test set.

1️⃣2️⃣ Finally, I evaluated the model's performance by calculating accuracy, generating a classification report, and visualizing the confusion matrix.

Moving forward, there are potential ways to further improve the model's accuracy. For example, by changing the parameters of the grid search or experimenting with alternative models, we can explore different avenues to boost accuracy. 🔄💡

Feel free to explore the project code provided in the repository above. If you have any questions or suggestions, please don't hesitate to reach out.
