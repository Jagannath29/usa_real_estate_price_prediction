# usa_real_estate_price_prediction
This is a machine learning that involves building a model to predict real_estate house price in usa using realtor-data.zip.csv from kaggle. This project covers all the typical machine learning steps, including data exploration, preprocessing, preparation, feature engineering model selection and model evaluation.


## Preprocessing
The shape of the dataset is  175154 rows and 13 columns

columns in the data sets are 'status', 'brokered_by', 'price', 'bed', 'bath', 'acre_lot', 'street',
       'zip_code', 'house_size', 'prev_sold_year', 'prev_sold_month',
       'prev_sold_day'

- Where
  - status: Status of the house i.e sold or not sold
  - price: Price of the house.
  - bed: How many bed are there inside house.
  - bath: How many toilets are there inside house.
  - city: In which city, house lies.
  - street: Address of the house
  - zip_code: zip code of address
  - prev_sold_date: date of the house that are previously sold.
  - acre_lot: square meter of the house.
  - brokered_by: arrange by the broker to sell the house

I visualized the null values using heatmap and filled the null values with median and dropped some rows which were not relevant.

There were some outliers in target varaible, I handled it too using median.

### outlier
-  An outlier is a data point that differs significantly from other observations.
-  for example:- 1,2,3,4,5,6,7,8,9,1000
  - here 1000 is an outlier

I build a function and applied like RandomForestRegressor, LinearRegression, KNeighborsClassifier, DecisionTreeRegressor algorithms.


## To run the project:
- git clone https://github.com/Jagannath29/usa_real_estate_price_prediction.git
- pip install -r requirements in the terminal






