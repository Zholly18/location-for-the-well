# location-for-the-well
## Location for the Well

## Project Description
This project was created to analyze exploration data and determine the most profitable region to drill new oil wells. We are working with data from three different regions and building a model to predict the amount of oil reserves based on the attributes provided.

## Data
Three datasets were used in the project:

- `geo_data_0.csv`.
- `geo_data_1.csv`
- `geo_data_2.csv`.

Each dataset contains the following columns:

- `id`: Unique identifier of the well
- `f0`, `f1`, `f2`: Features associated with the field
- `product`: Volume of reserves in the well (in thousands of barrels)

## Project Objectives
1. Conduct exploratory data analysis (EDA).
2. Train a linear regression model for each region.
3. Estimate the model on the validation sample and calculate the average oil reserve as well as the RMSE.
4. Calculate profits for selected wells based on model predictions.
5. Apply the Bootstrap technique to estimate risk and profit in each region.
6. Select the most profitable region to drill new wells.

## Libraries used
The following libraries were used in the project:

- `pandas`.
- `numpy`
- `matplotlib`
- `seaborn`
- `scikit-learn`

## How to start the project
To run the project on a local machine:

1. Clone the repository:
   ```bash
   git clone https://github.com/Zholly18/login-for-the-well.git
2. Install the necessary libraries (pip install) 
3. Start Jupyter Notebook.
4. Open the Selection of the well.ipynb file and execute all the cells.

Project author: Sergei Zholudev
Email: zholly18@gmail.com 
