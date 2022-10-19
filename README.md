
# House Price Prediction

Ask a home buyer to describe their dream house, and they probably won't begin with the height of the basement ceiling or the proximity to an east-west railroad. But this playground competition's dataset proves that much more influences price negotiations than the number of bedrooms or a white-picket fence.

### Dataset

With 79 explanatory variables describing (almost) every aspect of residential homes in Ames, Iowa. The aim is to predict the price of Homes.

### Python Libraries
- Numpy
- Pandas
- Matplotlib
- Scikit Learn
- Seaborn

### Problem Statement

The aim of building a machine learning model is to solve a problem and to define a metric to measure model performance. So, first of all I have to define the problem to be solved in this project. The problem is to model and house prices in Ames, Iowa. I have used two performance metrics MSE (Mean Square Value) and R2 Score value to compute our model performance.

### Target and Features
There are 79 features ana 1 target variable(Sale Price), After the data cleaning process and different fearure selection techniques, The final clean data is 15 feature variables and 1 target variable.

### Data Cleaning process
- Check for High and Low cardinality
- Check for columns with >50% null cells
- Check for Leakages
- Check for Multicollinearity
- Check for outliers

### Exploratory Data Analysis
After cleaning the dataset, a few explorations was done and the summary findings are:
- The average sale price is  ~ $160,000
- Houses in the NWAmes, NoRidge neighborhoods are more expensive on an average.
- The Building Type or House Type is not a strong factor that affects the price of the house, Location of the house takes precendence when pricing the house.

### Data Modelling

- The dataset was trainied using 5 different linear regression algorithms and the best model was selected using MSE and R Squared as evaluation criteria
- The selected model generalized better than other tested model.

### Communicating Results and Deployment

The IPwidgets on Jupyter was used to deployemt the model.

## Acknowledgements
 - [Stackoverflow](stackoverflow.com)
 - [Awesome README](https://github.com/matiassingers/awesome-readme)
 - [Geeks for Geeks](geeksforgeeks.org)

