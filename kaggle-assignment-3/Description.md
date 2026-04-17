MLP | Jan 26 | 2025 Kaggle Assignment-3

Predict the sentiment of the given movie review. Submit predictions for test data by learning from the training.

# Dataset Description

A movie review platform wants to analyze the sentiments of the different reviews posted by users of their platform. The review for the movie is given in the column "phrase" and it has been informed that it was used to generate three more features in the datasets.

The task will be a multi-class classification problem predicting the sentiment of the review

# Files

- train.csv - The training set which contains the features and the target
- test.csv - The test set for which the target column is hidden
- sample_submission.csv - A sample submission file in the correct format

# Columns

The dataset contains the following features:

id: The index column
phrase: Review text of the movie
feature_1
feature_2
feature_3
sentiment: Sentiment of the review with 0 for negative, 1 for neutral and 2 for positive

# Evaluation

Submissions are evaluated on accuracy between the observed target and the predicted target.

# Submission File

For each id in the test set, you must predict the value of the target variable. The file should contain a header and have the following format:

```
id,sentiment
0,1
1,1
2,1
etc.
```

# Rubrics, organized by criteria and specific requirements:

- **Identify Data Types (Weight: 5)**
  - Explicitly state the data types for every column within the notebook.
  - Failure to provide data type information results in 0 points.

- **Descriptive Statistics (Weight: 5)**
  - Provide summary statistics for all numerical columns.
  - Must include specific details: **minimum value**, **maximum value**, **mean**, and **median**.

- **Missing Values (Weight: 10)**
  - Identify all columns containing missing data.
  - Handle these values by either **dropping** the rows/columns or **imputing** the data.

- **Duplicates (Weight: 10)**
  - Scan the dataset for duplicate entries.
  - If duplicates exist, they must be identified and dropped.

- **Outliers (Weight: 10)**
  - Identify outliers within the dataset.
  - Provide a clear explanation/justification for whether you chose to **retain** or **drop** them.

- **Visualizations and Insights (Weight: 10)**
  - Present a minimum of **three** distinct visualizations.
  - Include a detailed analysis/insight for each visualization provided.

- **Scaling and Encoding (Weight: 10)**
  - Perform feature scaling on numerical data and encoding on categorical data.
  - Provide an explanation for the specific methods used (or a justification if you chose not to scale/encode certain variables).

- **Model Building (Weight: 20)**
  - Train at least **7 different types** of machine learning models on the processed data.
  - Scores are based on meeting the minimum count of seven unique algorithms.

- **Hyperparameter Tuning (Weight: 10)**
  - Select **3 of the models** from your previous step for optimization.
  - Perform hyperparameter tuning to improve those specific models.

- **Model Performance Comparison (Weight: 10)**
  - Compare the performance of all trained models.
  - Evaluation must be based on results from the **validation set**.
