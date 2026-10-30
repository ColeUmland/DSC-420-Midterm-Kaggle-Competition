# DSC-420-Midterm-Kaggle-Competition

Project Description and Details:
For this project, we competed in a Kaggle competition. The Kaggle competition offered a month long window to train a model and improve the Area Under the Curve (AUC), of a Receiver Operator Characteristic Curve (ROC) curve. 

We were given a data set containing information about flights and if the passengers were satisfied with their experience or not. There were several variables including many on in-flight experience and flight delays and logistics.

Goal: 
Practice the workflow of a Data Scientist from exploring data to building, evaluating, and communicating predictive models.

Models Used:
Logistic Regression, Random Forests, CATBoost

Training Method: Train & Test Splitting & K-Fold Cross Validation
We tried a train and test split before a k-fold cross validation technique to train our models.

Findings:

Model      | Logistic Regression | Random Forests | CATBoost |

Test AUC via Cross Validation  |       .9224         |      .95413    |   .9575  |
- Via Test Set AUC, CATBoost had the largest AUC on the test set, meaning it had the greatest predictive ability of our three models.
