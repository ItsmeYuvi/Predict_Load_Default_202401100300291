# Loan Default Prediction

## Overview

This project aims to predict the likelihood of loan defaults using machine learning techniques. By analyzing historical loan data, the model assists financial institutions in identifying high-risk borrowers, thereby minimizing potential losses.

## Dataset

The dataset used in this project is titled `1. Predict Loan Default.csv`. It contains various features related to loan applicants, including:

- **LoanID**: Unique identifier for each loan (removed during preprocessing).
- **Default**: Target variable indicating loan default status (1 = Default, 0 = No Default).
- **Other Features**: Various applicant and loan-related attributes (e.g., income, loan amount, credit score).

## Technologies Used

- **Python Libraries**:
  - `pandas`: Data manipulation and analysis.
  - `numpy`: Numerical computations.
  - `sklearn`: Machine learning models and preprocessing.
  - `matplotlib` & `seaborn`: Data visualization.
- **Google Colab**: Cloud-based Python execution environment.

## Installation

To run this project locally:

1. Clone the repository:

   ```bash
   git clone <repository_url>
   ```

2. Navigate to the project directory:

   ```bash
   cd <project_directory>
   ```

3. Install the required libraries:

   ```bash
   pip install pandas numpy scikit-learn matplotlib seaborn
   ```

4. Upload the dataset (`1. Predict Loan Default.csv`) to the environment.

## Usage

1. **Data Preprocessing**:
   - Load the dataset and remove the `LoanID` column.
   - Encode categorical variables using `LabelEncoder`.

2. **Model Training**:
   - Split the data into training and testing sets (80% train, 20% test).
   - Train a `RandomForestClassifier` with balanced class weights.

3. **Evaluation**:
   - Generate a classification report to assess model performance.
   - Plot a confusion matrix to visualize prediction accuracy.

4. **Feature Importance**:
   - Display a bar plot of feature importances to identify key predictors of loan defaults.

## Results

The model's performance metrics include:

- **Classification Report**: Provides precision, recall, f1-score, and support for each class.
- **Confusion Matrix**: Visual representation of true positives, false positives, true negatives, and false negatives.
- **Feature Importance Plot**: Highlights the most influential features in predicting loan defaults.

## Business Recommendations

Based on the model's findings, financial institutions can consider the following:

- **Enhanced Credit Assessment**: Focus on key features identified as significant predictors.
- **Risk-Based Loan Approval**: Implement stricter criteria for applicants with high-risk factors.
- **Continuous Monitoring**: Regularly update the model with new data to maintain prediction accuracy.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Screenshots
![Screenshot 2025-04-18 144836](https://github.com/user-attachments/assets/ddd494b9-66ae-4e16-87e4-b095809eaf5c)
