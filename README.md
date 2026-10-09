# Water Shortage Risk Prediction Using Machine Learning

## Project Overview
This project uses machine learning to predict water shortage risk based on factors such as population, rainfall, agricultural land, industrial and domestic water usage, groundwater levels, reservoir capacity, and total water consumption.

A **Logistic Regression** model is used to classify water shortage risk into two categories: Yes or No.

## Objective
To develop a machine learning model that identifies potential water shortage risks using environmental, demographic, and water consumption data, supporting better water resource planning and management.

## Dataset Description
The dataset `water_shortage_balanced.csv` contains **5,000 records and 11 columns**.

**Features:**
- State
- Year
- Population
- Annual Rainfall
- Agricultural Land
- Industrial Water Usage
- Domestic Water Usage
- Groundwater Level
- Reservoir Capacity
- Total Water Consumption

**Target Variable:** `Water Shortage Risk` (Yes/No)

## Technologies Used
- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-learn
- Google Colab

## Methodology
1. Load and explore the dataset.
2. Check data types, descriptive statistics, and missing values.
3. Encode categorical variables using Label Encoding.
4. Remove the Year column.
5. Separate input features and the target variable.
6. Split the dataset into 80% training and 20% testing data.
7. Standardize the features using StandardScaler.
8. Train a Logistic Regression model.
9. Evaluate the model using accuracy, a classification report, and a confusion matrix.

## Model Performance
The Logistic Regression model achieved **98.1% accuracy** on the test dataset of 1,000 records.

- **Precision:** 98% macro average
- **Recall:** 98% macro average
- **F1-score:** 98% macro average

These results reflect the model's performance on the current test split.

## How to Run
1. Open the notebook in [Google Colab](https://colab.research.google.com/).
2. Upload the notebook and `water_shortage_balanced.csv`.
3. Ensure the dataset path is correct.
4. Run all cells sequentially.



## Future Improvements
- Develop a user-friendly interface using Streamlit or Flask.
- Add visualizations to explore water shortage trends.
- Compare Logistic Regression with other classification algorithms.
- Test the model on additional real-world water resource data.
- Support data-driven water conservation and planning decisions.



---

*Applying machine learning to support water resource management and shortage risk prediction.*
