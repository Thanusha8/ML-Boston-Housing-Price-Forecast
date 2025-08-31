# ML-Boston-Housing-Price-Forecast



## 📊 Dataset Description

The Boston Housing Dataset contains information collected by the U.S. Census Service concerning housing in the area of Boston, Mass. It has 506 instances and 13 features, with one target variable.

**Features (Independent Variables):**
- **CRIM:** Per capita crime rate by town
- **ZN:** Proportion of residential land zoned for lots over 25,000 sq.ft.
- **INDUS:** Proportion of non-retail business acres per town
- **NOX:** Nitric oxides concentration (parts per 10 million)
- **RM:** Average number of rooms per dwelling
- **AGE:** Proportion of owner-occupied units built prior to 1940
- **DIS:** Weighted distances to five Boston employment centres
- **RAD:** Index of accessibility to radial highways
- **TAX:** Full-value property-tax rate per $10,000
- **PTRATIO:** Pupil-teacher ratio by town
- **BLACK:** `1000(Bk - 0.63)^2` where Bk is the proportion of Black residents by town
- **LSTAT:** % lower status of the population

**Target (Dependent Variable):**
- **MEDV:** Median value of owner-occupied homes in $1000's

## 🛠️ Tech Stack

- **Language:** Python
- **Libraries:** Pandas, NumPy, Scikit-Learn, Matplotlib/Seaborn (for visualization, if added later)
- **Environment:** Jupyter Notebook

## 🔧 Implementation

The project follows a standard machine learning workflow:

1.  **Data Loading & Inspection:** Loaded the dataset and performed initial exploration.
2.  **Data Preprocessing:** Split the data into features (`X`) and target (`y`).
3.  **Train-Test Split:** Divided the data into training (80%) and testing (20%) sets.
4.  **Model Training:** Trained a Linear Regression model on the training set.
5.  **Prediction & Evaluation:** Made predictions on the test set and evaluated model performance using:
    - **R² Score (Coefficient of Determination)**
    - **Mean Squared Error (MSE)** 
    - **Root Mean Squared Error (RMSE)** 


## 🚀 How to Run

1.  Ensure you have Python and Jupyter Notebook installed.
2.  Install the required libraries:
    ```bash
    pip install pandas numpy scikit-learn matplotlib seaborn jupyter
    ```
3.  Clone this repository and navigate to its directory.
4.  Launch Jupyter Notebook:
    ```bash
    jupyter notebook
    ```
5.  Open the `Linear regression.ipynb` notebook and run all cells.
