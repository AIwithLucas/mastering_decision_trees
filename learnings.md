# 1 Decision Tree Classifier Learnings

#### 1. Analyzing missing data in features help to provide better understanding of loan-related application process

    - eg: Why there are 8505 missing values in joint_account application because most people are applying individually

#### 2. Imbalanced dataset cases model accuracy to be very high just by predicting all as Current (class imbalance)

- Current 9354
- Fully Paid 445
- In Grace Period 66
- Late (31-120 days) 66
- Late (16-30 days) 38
- Charged Off 7

  #### Solution:

  ##### 1. Use alternative metrics

        - use alternative metrics like Precision, Recall & F1-Score
        - use confusion matrix for multi-class to visualize

  ##### 2. Resample data

        - Oversample the minority classes: use SMOTE -> Synthetic Minority Oversampling Technique or simple duplication of minority classes
        - Undersample the majority class -> perform random sampling to balance the dataset

  ###### 3. Assign weights

        - Assign higher weights to minority classes during model training

##### 4. Feature importance technique

      - after resampling data, need to consider techniques on finding feature importance, especially if a lot of features involved

# 2 Decision Tree Regressor Learnings

       Prediction Outcomes:
       - Will only have groups of predicted values
       eg:

            52.07387096774194,
            73.44415254237288,
            88.10335766423357,
            107.4423163841808,
            121.33392857142857,
            139.9335294117647,
            158.26336283185842,
            180.71446808510638

      Any data value out of this range of values cannot be predicted accurately
