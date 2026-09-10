# Student Performance Prediction Using Machine Learning

## Objective

The objective of this project is to predict whether a student will pass or fail based on student-related academic, demographic, family, and social factors.

## Dataset

The dataset used is the Student Performance dataset (`student-por.csv`).

- Number of records: 649
- Number of features: 33
- Target variable: G3
- Pass: G3 >= 10
- Fail: G3 < 10

G1 and G2 were removed because they represent previous grades.

## Machine Learning Algorithms

Three classification algorithms were applied:

1. Logistic Regression
2. Decision Tree Classifier
3. Gaussian Naive Bayes

## Evaluation Metrics

The models were evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix

## Results

The performance of the three algorithms was compared using the above evaluation metrics.

The best-performing algorithm was selected based on the F1 Score.

## Visualizations

The project includes:

- Decision Tree visualization
- Confusion matrices
- Model performance comparison

## Conclusion

The three machine learning algorithms were successfully applied to the Student Performance dataset. Their performance was evaluated and compared using suitable classification metrics. The model with the highest F1 Score was identified as the best-performing algorithm.