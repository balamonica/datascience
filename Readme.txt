Title: Real estate analytics
Dataset: Home buyer preference data of IOWA
Description:
The project aims to find the factors that influence the price negotiations while buying a house in IOWA. There are in total 79 varibles. In this project, the data is thoroughly analysed to determine the influence of different variables on buyers choice. Some key steps followed include
---> Data is first analysed to determine the variables with null value
---> Categorical data and numerical data is seperated
---> The null values are replaced appropriately for categorical as well as numerical missing values
---> LAmbda function is used then and there to replace the null values
---> Correlation matrix is constructed to determine the variables that influence the price
---> Factors with correlation coefficient greater than 0.4 is chosen as key factors
---> These include 'LotFrontage', 'OverallQual', 'YearBuilt', 'YearRemodAdd', 'MasVnrArea',
       'TotalBsmtSF', '1stFlrSF', 'GrLivArea', 'FullBath', 'TotRmsAbvGrd',
       'Fireplaces', 'GarageCars', 'GarageArea', 'SalePrice'
---> The target variable 'SalePrice' is highly correlated with OverallQual of the house, Garage Cars, Garage area, TotRmsabovgrnd, TotalBsmSF, 1stflrSF,Yearbuilt and remodelled, MasVnrArea and Fullbath
---> Function is written to determine the outliers in any data
---> Pairplot is constructed to determine the influence of different variables on sale price

INSIGHTS

---> The overall quality affects the SalePrice -higher qualtity houses have been sold for higher prices
---> The distribution plot shows that 750-1250 sq ft basement area is the most sorted options
---> The properties with 3 garage car parking space is the highest selling property in iowa