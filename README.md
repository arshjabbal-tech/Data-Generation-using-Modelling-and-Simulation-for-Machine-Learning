# Data Generation using Modelling and Simulation for Machine Learning

## Simulation Tool
NetLogo (Wolf–Sheep Predation Model)

## Objective
To generate data using simulation and apply machine learning models to analyze and predict system behavior.

---

## Step 1: Simulator Selection
NetLogo was selected due to its wide use in agent-based modeling and ease of generating controlled simulation data.

---

## Step 2: Model Description
The Wolf–Sheep Predation model simulates interactions between predator (wolves) and prey (sheep) populations over time.

---

## Step 3: Parameters Used

- Initial Sheep Population
- Initial Wolf Population
  
---

## Step 4: Data Generation
Multiple simulations were executed using NetLogo BehaviorSpace.
Simulation results were exported in CSV format.

Dataset includes:
- Sheep population
- Wolf population
- Simulation step

---

## Step 5: Machine Learning Models
The following ML models were applied:

- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor
- K-Nearest Neighbors
- Support Vector Regressor

---

## Step 6: Evaluation Metrics
Models were evaluated using:
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- Mean Absolute Error (MAE)
- R² Score

---

## Results
The best performing model was selected based on lowest error metrics.

## Simulation Output Tables

### Dataset Table
![Dataset Table](images/table_results.png)

### Simulation Results
![Simulation Output](images/simulation_output.png)

---

## Tools & Libraries
- NetLogo
- Python
- Pandas
- Scikit-learn
- Google Colab

---

## Repository Structure
