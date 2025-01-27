# Stroke Prediction Project

 This project focuses on analyzing health-related data to predict the likelihood of a stroke using machine learning techniques. It involves data preprocessing, handling imbalanced datasets, building predictive models, and evaluating their performance.

---

## Libraries Used

The following libraries are essential for this project:

- **Data Manipulation and Analysis**:
  - `numpy`
  - `pandas`

- **Visualization**:
  - `matplotlib`
  - `seaborn`

- **Machine Learning and Preprocessing**:
  - `sklearn` (train-test splitting, preprocessing, metrics, etc.)
  - `statsmodels` (logistic regression analysis)
  - `imbalanced-learn` (SMOTE for handling imbalanced data)

---

## Project Workflow

1. **Data Preprocessing**:
   - Handle missing values and encode categorical data.
   - Split the dataset into training and testing sets.

2. **Addressing Imbalance**:
   - Use SMOTE (Synthetic Minority Oversampling Technique) to balance the dataset.

3. **Model Building**:
   - Train a logistic regression model using `statsmodels`.

4. **Evaluation**:
   - Evaluate the model using metrics like:
     - Precision
     - F1-Score
     - ROC Curve (AUC Score)
   - Confusion Matrix for classification performance.

---

## Results

The project includes:
- Detailed classification metrics.
- Visualization of the ROC curve and performance metrics.


