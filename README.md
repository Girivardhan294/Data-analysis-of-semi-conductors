# Semiconductor Manufacturing Process - ML Model Comparison

This project focuses on evaluating and comparing three different machine learning algorithms applied to a classification problem within the semiconductor manufacturing process. The comparison aims to identify which algorithm performs best under a class imbalance scenario, where one class (e.g., class 1) is significantly underrepresented.

## Models Compared:
1. **Random Forest**
2. **Support Vector Machine (SVM)**
3. **Naive Bayes**

## Dataset
The dataset used for training the models contains a significant class imbalance, with class -1 being the majority class and class 1 being the minority class. The task involves predicting whether a sample belongs to class -1 or class 1 based on several features.

## Key Results
- **Random Forest and SVM**: Both models exhibit high overall accuracy but fail to effectively predict the minority class (class 1). These models are biased towards predicting the majority class (-1).
- **Naive Bayes**: This model demonstrates poor overall performance but achieves higher recall for the minority class (class 1), showing that it can handle class imbalance better than Random Forest and SVM, though at the cost of overall accuracy.

## Conclusion
- **Class Imbalance Challenge**: All models face difficulty in handling the class imbalance, particularly Random Forest and SVM. Naive Bayes performs better in identifying minority class examples but lacks in overall prediction power.
- **Future Work**: Addressing class imbalance through techniques like oversampling, undersampling, or cost-sensitive learning could improve model performance, especially for minority class detection.

## Dependencies
- Python 3.x
- Scikit-learn
- Pandas
- Jupyter Notebook

## Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/Girivardhan294/semiconductor-manufacturing-process.git


