# AI-Based Water Quality Prediction

## Project Overview
This project uses machine learning to predict water potability categories from physicochemical water-quality parameters. It demonstrates how data analysis and classification algorithms can be applied to water-quality datasets.

## Objective
- Analyze water-quality parameters using Python.
- Train machine learning models to classify water samples.
- Compare Random Forest and Decision Tree performance.
- Explore which features contribute most to model predictions.

## Dataset
- **Source:** [Kaggle — Water Potability Dataset](https://www.kaggle.com/datasets/adityakadiwal/water-potability)
- **Target column:** `Potability`
- **Class 0:** Non-potable label
- **Class 1:** Potable label

## Technologies Used
- Python
- Pandas and NumPy
- Matplotlib
- Scikit-learn
- Google Colab

## Methodology
1. Load and inspect the dataset.
2. Handle missing values using median imputation.
3. Separate features and target labels.
4. Split the data into training and testing sets.
5. Train Random Forest and Decision Tree classifiers.
6. Evaluate models using accuracy, precision, recall, F1-score, and a confusion matrix.
7. Visualize model accuracy and feature importance.
8. Test predictions using sample water-quality measurements.

## Initial Results
The initial Random Forest model achieved **67.07% test accuracy**.

For Class 1, the initial recall was **29.30%**, indicating that the model missed many samples belonging to that class. The Decision Tree model and threshold experiments should be evaluated using their actual measured results before drawing further conclusions.

## Limitations
- Dataset labels are not a substitute for laboratory water-quality testing.
- Model predictions do not certify that water is safe to drink.
- Performance may vary with data quality and the samples used for training and testing.
- Further validation and model improvement are needed.

## Future Scope
- Improve minority-class detection.
- Compare additional classification algorithms.
- Use cross-validation and careful hyperparameter tuning.
- Evaluate probability calibration and model robustness.
- Explore validated water-quality standards and independent datasets.

## Author
https://github.com/Sakshigorde
