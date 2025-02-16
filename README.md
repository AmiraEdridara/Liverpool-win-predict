# Liverpool Win Prediction

This project predicts Liverpool's position and points for the 2024-2025 season using machine learning. It uses a **Random Forest Regressor** to make predictions based on historical data.

---

## Table of Contents
1. [Introduction](#introduction)
2. [Dataset](#dataset)
3. [Methodology](#methodology)
4. [Usage](#usage)
5. [Results](#results)
6. [License](#license)

---

## Introduction
The goal of this project is to predict Liverpool's position and points for the 2024-2025 season using historical data. The model is trained on features like wins, losses, draws, goal difference, and win probability.

---

## Dataset
The dataset (`liverpoolsheet.csv`) includes the following features for each season:
- **Wins**: Number of matches won.
- **Losses**: Number of matches lost.
- **Draws**: Number of matches drawn.
- **Win Probability**: Percentage of matches won.
- **Goal Difference**: Difference between goals scored and conceded.
- **Actual Position**: Liverpool's final position in the league.
- **Actual Points**: Total points earned in the season.

---

## Methodology
1. **Data Preprocessing**:
   - Cleaned and preprocessed the dataset (e.g., converted win probability to float).
2. **Model Selection**:
   - Used **Random Forest Regressor** for both position and points prediction.
3. **Training and Evaluation**:
   - Split the data into training and testing sets.
   - Evaluated the model using **RMSE** and **R² Score**.
4. **Predictions**:
   - Predicted Liverpool's position and points for the 2024-2025 season.

---

## Usage
1. Open the Jupyter Notebook (`Liverpool_Win_Prediction.ipynb`).
2. Run all cells to:
   - Train the models.
   - Make predictions for the 2024-2025 season.

---

## Results
- **Position Model**:
  - RMSE: 1.23
  - R² Score: 0.95
- **Points Model**:
  - RMSE: 5.67
  - R² Score: 0.92
- **2024-2025 Predictions**:
  - Predicted Position: 1.50
  - Predicted Points: 89.30

---

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

