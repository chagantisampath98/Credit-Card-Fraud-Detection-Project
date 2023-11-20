# Credit-Card-Fraud-Detection-Project
The provided Python script is designed for credit card fraud detection using a logistic regression model. The initial section focuses on data exploration and loading. It imports necessary libraries, reads a credit card dataset, and displays the dataset's shape along with the first few rows. This gives an overview of the data structure and content.

Following the data exploration, the script provides insights into the dataset by presenting information such as data types, summary statistics, and the distribution of the target variable (fraud or not fraud). Visualization plays a crucial role, as the script generates plots for selected features to visualize their time series patterns, aiding in better understanding the data.

The data preparation step involves splitting the dataset into features and the target variable. The scikit-learn library's `train_test_split` function is then used to create training and testing sets, which are essential for training and evaluating the machine learning model.

The script employs a logistic regression model for fraud detection. It trains the model using the training set and evaluates its performance on the test set. The confusion matrix is generated and visualized using a heatmap, offering a clear representation of the model's predictive accuracy. Furthermore, two important metrics, sensitivity (recall) and F1 score, are calculated and printed to assess the model's effectiveness in identifying fraudulent transactions.

In conclusion, the script provides a comprehensive pipeline for credit card fraud detection, encompassing data exploration, visualization, model training, and evaluation. The logistic regression model demonstrates a reasonable level of accuracy, as evidenced by the sensitivity and F1 score metrics, making it a valuable tool in identifying potential instances of fraud in credit card transactions.
