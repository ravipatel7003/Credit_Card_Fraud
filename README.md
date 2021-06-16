# Credit Card Fraud Detection Model

Nowadays, credit card frauds are common. With the improvement in the lifestyle and use of technology increased use of credit cards for shopping and getting cash. People prefer to keep a single card that can hold their money and use it whenever and wherever they want than carrying money everywhere. This created an opportunity for the hackers to illegitimately use your credit card without you knowing. In this project, we used a Machine Learning model to classify fraudulent transactions from normal transactions.

## Dataset
The Dataset used in the project is taken from Kaggle. The dataset contains two days of transactions made by European cardholders in September 2013. The dataset contains 284,807 transactions, among which 284,315 are normal and 492 are fraudulent. No wonder why the dataset is highly imbalanced as it represents the real world, where normal transactions are way more than fraudulent.

The Dataset contains 30 features and 1 target/class column.  For confidentiality reasons, 28 out of 30 features are taken using PCA techniques, only "Time" and "Amount" are in original form. The "Time" represents the number of seconds between the first transaction in the dataset and itself. The "Amount" represents the value that was used in the transaction. All the features are numeric features with zero missing values.

## Training and Testing
In the beginning, we split the data into 80% training and 20% test datasets. Then, all the analysis and training happened on the training dataset. The test dataset was used only in the end for the evaluation. During the model training, the training set was again split into two datasets, training and validation. The training was used to train the models and validation is used to evaluate models and select the best performing model for final evaluation.

Due to the high imbalanced data, we used Area Under the Precision-Recall Curve and plotted a confusion matrix and classification report for the test dataset for more detailed understanding.


## Contributing
Pull requests are welcome.
