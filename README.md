Group project for INFO3300.

We were interested in learning about the quality of life on the state and county level, and the factors that contribute to it. 
We found a dataset on Kaggle.com, described as “Every metric we could think to rank a city with, all in one neat pile!” It includes variables such as Population, City Type (Rural, Suburb, etc.), Unemployment, Cost of Living, Median Income, Crime Rates, Air Quality and Water Quality, and School Diversity. 
We focused on the unemployment field. We also needed a more general dataset to quantify overall quality of life. We used the 2023 Quality of Life By State dataset from the World Population Review, which included quality of life scores for different categories, such as safety, education, and economy. We singled out the “Quality of life Total Score” field to use in our country-level visualization. 
Finally, we used a json file from US Atlas TopoJSON to define the county and state boundaries.

To run program:
python -m http.server
