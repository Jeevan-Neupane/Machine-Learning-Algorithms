# Machine-Learning-Algorithms

## 1. Simple linear Regression


This project demonstrates the implementation of **Simple Linear Regression** to predict salaries based on years of experience. The dataset used is `Salary_Data.csv`, which contains two columns: `YearsExperience` and `Salary`.

---

### Project Overview
**Simple Linear Regression** is used to predict a dependent variable (`Salary`) based on an independent variable (`YearsExperience`). This project includes:
- Training a model using a linear regression algorithm.
- Evaluating model performance.
- Deploying the model as an API using **FastAPI** and **ngrok** for public accessibility.

---

### Dataset
The dataset `Salary_Data.csv` contains 30 entries with the following columns:
- **YearsExperience**: Number of years of experience.
- **Salary**: Salary of the individual.

Sample data:
| YearsExperience | Salary     |
|-----------------|------------|
| 1.1            | 39343.0    |
| 1.3            | 46205.0    |
| 1.5            | 37731.0    |
| 2.0            | 43525.0    |
| 2.2            | 39891.0    |

---

### Dependencies
Install the required libraries using:
```bash
pip install numpy pandas matplotlib scikit-learn fastapi uvicorn joblib

```




## 2. Multiple Linear Regression

This project demonstrates the implementation of **Multiple Linear Regression** using Python. The dataset used is the **50 Startups Dataset**, which helps predict the profit of startups based on their R&D Spend, Administration costs, Marketing Spend, and the state in which they operate.

--


### Project Overview
The goal of this project is to:
1. Explore the relationship between startup expenses and profits.
2. Build a **Multiple Linear Regression Model** to predict startup profit.
3. Use **Backward Elimination** for feature selection to create an optimized model.

---

### Dataset
The dataset `50_Startups.csv` contains the following columns:
- **R&D Spend**: Money spent on research and development.
- **Administration**: Money spent on administration.
- **Marketing Spend**: Money spent on marketing.
- **State**: The state in which the startup operates.
- **Profit**: The profit of the startup (target variable).

---

### Dependencies
Ensure you have the following libraries installed before running the project:
- Python 3.x
- Pandas
- NumPy
- Matplotlib
- scikit-learn
- statsmodels

Install dependencies via:
```bash
pip install numpy pandas matplotlib scikit-learn statsmodels
