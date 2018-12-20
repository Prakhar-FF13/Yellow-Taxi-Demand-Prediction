# Yellow Taxi Demand Prediction

## Task -

Given previous info about number of pickups in regions, predict the expected number of pickups in the next 10 minute interval

## Steps - 

1. Convert the given time series data into 10 minute interval bins.
2. Break the region of new york city into some clusters say k.
3. Group the time series data for each cluster.
4. Apply any feature engineering techniques to generate some more time series features.
5. Perform Train-Test Split.
6. Train Models.
7. Evaluate and Display MAPE in Tabular Format for all the models built.

## Conclusion - 

1. XgBoost Had the least MAPE of around 10 %
2. Winter Holts Triple Exponential Features helped to achieve the results.
