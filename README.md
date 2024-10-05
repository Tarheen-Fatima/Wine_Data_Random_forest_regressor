# Wine Data Prediction using Random Forest Regressor

This project uses the **Wine dataset** to build a **Random Forest Regressor** model that predicts one of the features of wine, such as **Alcohol Content** (or any other numerical feature you select), based on other chemical features of the wine. The dataset is split into training and testing sets, and the performance of the model is evaluated using metrics like **Mean Squared Error (MSE)** and **R² score**.

## Dataset

The dataset used in this project is the **Wine dataset**, which is available in the `sklearn.datasets` module. The dataset contains 13 chemical properties of wine, such as:

- Alcohol
- Malic Acid
- Ash
- Alcalinity of ash
- Magnesium
- Total phenols
- Flavanoids
- Nonflavanoid phenols
- Proanthocyanins
- Color intensity
- Hue
- OD280/OD315 of diluted wines
- Proline

The target feature used in this project is **Alcohol content**  and the rest of the features are used to predict it.

## Project Structure

The following steps are performed in this project:

1. **Data Loading:** The Wine dataset is loaded from the `sklearn.datasets` module.
2. **Data Preprocessing:** The dataset is checked for missing or duplicated values and split into training and testing sets.
3. **Model Building:** A **Random Forest Regressor** model is built using the training data.
4. **Model Evaluation:** The model is evaluated using the testing data, and metrics like **Mean Squared Error (MSE)** and **R² score** are calculated.
5. **Data Visualization:** The actual vs predicted values are visualized using **matplotlib**.

## Model Evaluation

- **Mean Squared Error (MSE):** A metric that shows the average squared difference between actual and predicted values.
- **R² Score:** A metric that shows how well the model's predictions match the actual data (higher is better, with 1 being a perfect score).
