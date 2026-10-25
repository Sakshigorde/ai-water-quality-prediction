# AI-Based Water Quality Prediction
## Project Overview
I built this project to explore how machine learning can be used to predict water potability based on water-quality parameters. I used Python to analyze the dataset and trained two models: Random Forest and Decision Tree.

## Objective
- Understand and analyze water-quality data.
- Build machine learning models to predict water potability.
- Compare the performance of Random Forest and Decision Tree.
- Identify which water-quality parameters are important for prediction.
## Dataset
- **Source:** [Kaggle — Water Potability Dataset](https://www.kaggle.com/datasets/adityakadiwal/water-potability)
- **Target column:** `Potability`
- **Class 0:** Non-potable label
- **Class 1:** Potable label


## Tools and Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Google Colab

## Methodology
## What I Did
1. Loaded and explored the Kaggle dataset.
2. Checked for missing values and filled them using the median.
3. Split the data into training and testing sets.
4. Trained Random Forest and Decision Tree models.
5. Compared model performance using accuracy, precision, recall, and F1-score.
6. Created graphs to visualize model accuracy and feature importance.
7. Tested the model with sample water-quality values.

## Results
The Random Forest model achieved **67.07% accuracy** on the test set.
The recall for Class 1 was **29.30%**, which means the model failed to identify many samples belonging to this class. This shows that the model still needs improvement.
I also trained a Decision Tree model to compare its performance with Random Forest.
## Limitations
- The model does not predict every sample correctly.
- The dataset contains missing values.
- The model has difficulty identifying Class 1 samples.
- Predictions cannot confirm whether water is safe to drink; laboratory testing is required.
## Future Improvements
- Improve the model's prediction performance.
- Try other machine learning algorithms.
- Handle class imbalance more effectively.
- Test the model using other water-quality datasets.
- Explore its use in water-quality monitoring...

## Author
https://github.com/Sakshigorde
