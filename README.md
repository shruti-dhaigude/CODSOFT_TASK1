# CODSOFT_TASK1

## Mobile Price Classification

### CodSoft Machine Learning Internship – Task 1

### Project Objective

This project develops a machine learning classification model to predict the price category of a mobile phone based on its specifications such as RAM, battery power, internal memory, camera, screen resolution, processor cores, and connectivity features.

### Dataset

- 2,000 mobile phone records
- 20 input features
- 1 target variable: `price_range`
- 4 target classes: 0, 1, 2, 3
- No missing values

### Machine Learning Models

The following classification algorithms were tested:

1. Logistic Regression
2. Decision Tree
3. Random Forest
4. K-Nearest Neighbors (KNN)

### Results

The models were evaluated using test-set accuracy.

| Model | Accuracy |
|---|---:|
| Logistic Regression | 67.5% |
| Decision Tree | 83.0% |
| Random Forest | 88.0% |
| KNN | 93.5% |

KNN achieved the highest accuracy among the tested models, with **93.5% test accuracy**.

### Evaluation

The KNN model was further evaluated using:

- Confusion Matrix
- Classification Report

The classification report showed approximately **94% accuracy** on the 400 test samples.

### Tools & Technologies

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

### Conclusion

The project demonstrates how machine learning can use mobile phone specifications to classify phones into different price categories. Among the tested models, KNN provided the highest test accuracy of 93.5%.

### Author

**Shruti Dhaigude**

CodSoft Machine Learning Internship – September 2026
