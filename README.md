## Assignment Overview
Created by: 46765 Machine Learning for Energy systems Group 09

|       Name       | Student Number |
|:----------------:| :------------- |
|  Ilse de Droog   | 241950        |
|  Zheng Dong | 232281 |
| Gaurav Patnaik | 242657 |
| Charlotte Hessels | 242925
| Matthias Gröller | 242880    |



In order to investigate the issue of trading wind energy in day-ahead and balancing markets, this assignment compares two models: 1) employing forecasts of wind power production before tackling the decision-making problem, and 2) using data-driven methods to directly determine the most effective bidding strategy. Along with the impact of regularisation, the approach combines a deterministic optimisation model with linear and non-linear data-driven techniques.


```


### Step 1 data: preparation
This project works with some confidential data which for that reason cannot be uploaded to GitHub. In order to run these models please request access to the *Bornholm Network Manager Historical Wind Data* dataset from energydata.dk . Request data from 01-01-2022 up to and including 31-12-2022. Name the file Bornholm 2022 and save it in the folder Data assignment 1. 


To ensure you are working with the proper and clean data run the notebooks in the 'Data process' in the following order:
- Bornholm Data cleaning.ipynb
- Weather data.ipynb
- Datacleaning_Prices.ipynb
- Data_Cleaning_forcasted_Weather_data.ipynb
- Merging data.ipynb

*Note: Make sure to install the Jupyter Plug-in when using Pycharm. 
This will allow you to open .Ipynb notebooks.

### Step 2: model 1
Model 1 will develop an optimization model for renewable energy trading in day-ahead and balancing markets. Once the required data has been cleaned, the potential power production is predicted through linear and non-linear regression, after which the optimal revenue is calculated. 

Run model1.ipynb for the feature scaling, linear and non-linear and the bonus assignment. 
For step 6, Revenue calculation for evaluation, run Revenue_Calculation.ipynb

### Step 3: model 2
Model 2 leverages regression to directly determine the most effective offering strategy. 
model2.ipynb contains the clustering and regression applicable to model 2. 

