# MLP | Term-1 | 2026 Kaggle Assignment - 1

Use the training data provided to train your model and make predictions on the test data for which the test labels will be hidden.

## Evaluation

Submissions are evaluated on r2_score between the observed target and the predicted target.

### Submission File

For each ID in the test set, you must predict a probability for the TARGET variable. The file should contain a header and have the following format:

```
id,total_amount
0,24.45
1,25.53
2,108.76
etc.
```

## Dataset Description

Develop predictive models to estimate the total amount paid by travelers for taxi rides.

### Dataset Overview

This dataset presents an opportunity to construct predictive models aimed at estimating the total amount paid by travelers for taxi journeys. With access to a training set containing the target variable 'total_amount' along with various informative features, participants are challenged to create accurate predictive models.

### Data Files

The dataset is composed of the following files:

train.csv: The training set, which includes the target variable 'total_amount' and accompanying feature attributes.

test.csv: The test set, containing similar feature attributes but without the target variable 'total_amount,' as it is the variable to be predicted.

sample_submission.csv: A sample submission file provided in the correct format for competition submissions.

### Columns Description

The dataset comprises various columns, each offering valuable insights into taxi rides. Notably:

total_amount: The total amount paid by the traveler for the taxi ride.

VendorID: An identifier for taxi vendors.

tpep_pickup_datetime and tpep_dropoff_datetime: Timestamps indicating pickup and dropoff times.

passenger_count: The number of passengers during the ride.

trip_distance: The distance traveled during the trip.

RatecodeID: Rate code for the ride.

store_and_fwd_flag: A flag indicating whether the trip data was stored and forwarded.

PULocationID and DOLocationID: Pickup and dropoff location identifiers.

payment_type: Payment type used for the ride.

Other columns are self-explanatory and contribute to the modeling process.

Participants are encouraged to leverage these informative columns to build robust predictive models and contribute to the challenge of predicting the total fare amount accurately.

Your solutions should aim to enhance the accuracy and efficiency of total fare amount predictions for taxi rides.

## Peer Review Rubrics

### 1. Identify data types of different columns

- **Weight:** 5
- **Criteria:** The data types of the different columns are identified and explicitly stated in the notebook.

### 2. Present descriptive statistics of numerical columns

- **Weight:** 5
- **Criteria:** Details such as min value, max value, mean and median for each numerical column is presented.

### 3. Identify and handle the missing values

- **Weight:** 10
- **Criteria:** Missing values are identified and are dropped or imputed.

### 4. Identify and handle duplicates

- **Weight:** 10
- **Criteria:** Duplicates are identified and are dropped if they exist.

### 5. Identify and handle outliers

- **Weight:** 10
- **Criteria:** Outliers are identified and explanation for retaining / dropping is provided.

### 6. Present at least three visualizations and provide insights for the same

- **Weight:** 10
- **Criteria:** At least three visualizations on the data is presented.

### 7. Scale Numerical features and Encode Categorical features

- **Weight:** 10
- **Criteria:** Explanation for scaling (or not scaling) and encoding (or not encoding) is provided.

### 8. Model Building (at least 7)

- **Weight:** 20
- **Criteria:** 7 different types of models are trained on the data.

### 9. Hyperparameter Tuning on any 3 of the models

- **Weight:** 10
- **Criteria:** Hyperparameter tuning is done on 3 of the models.

### 10. Comparison of model performances

- **Weight:** 10
- **Criteria:** Performance of the models on validation set is compared.
