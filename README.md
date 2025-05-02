# SVR Salary Prediction with 3D Visualization

This project demonstrates how Support Vector Regression (SVR) can be used to predict employee salaries based on position levels. It includes preprocessing, model comparison (Linear, Polynomial, and SVR), and a 3D plot to help visualize SVR predictions.

## 🔍 What This Project Does

- Loads a small dataset of position levels and corresponding salaries
- Applies feature scaling to work with SVR
- Fits and compares:
  - Linear Regression
  - Polynomial Regression
  - SVR with different kernels
- Predicts salary for a specific level (e.g., 6.5)
- Visualizes SVR model predictions in both 2D and 3D
- Provides a function to tune SVR hyperparameters and view the effect on predictions

## 📊 Visual Output

- 2D plot: Compare predictions of Linear, Polynomial, and SVR models
- 3D plot: View the SVR "tube" prediction surface and adjust its shape using `C`, `gamma`, and `epsilon`

![image](https://github.com/user-attachments/assets/5b948171-2df8-4254-9cf0-2b48e57bb5b0)
![image](https://github.com/user-attachments/assets/588bbe08-578f-486f-8ec7-bc1d6cac6261)
