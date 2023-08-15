# Final-Project-Tableau

## Project/Goals
Analyse the trend of the housing market over time and compare the housing market in different states as well as different factors such as consumer price index and average income level.

## Process
- Loading Data Into Tableau
    - 4 CSVs
        - Consumer Index, Housing Price Index, Office Real Estate Index, Real Estate Numbers
    - 1 Excel
        - Real Estate Prices
    - 1 JSON
        - Weekly earnings
        - Created a script to combine column titles and data rows in Python

- Making sense of data
    - Convert dates into Date data types
    - Convert regions into City + States (Office + Real estate prices)
    - Merge many Excel sheet into one table
    - Understand which values are usable
        - For consumer index, two types of values: Percent and Index

- Creating Visualizations
- Finding Patterns
- Drawing conclusions


## Results
Tableau Public Link: https://public.tableau.com/app/profile/yuchen.he8057/viz/TableauProject_16921245913280/HousePriceDifferencevsEarningDifference?publish=yes
- Trend of house prices across Canada in the last 40 years
![Housing Price Trend](./charts/House%20Price%20Trend.png)
- Trend of house prices after 2005 with actual benchmark prices 
![Housing Price Compare](./charts/House%20Price%20Compare.png)
- Trend of house prices vs office prices
![Housing vs Office](./charts/House_Office%20Price%20Compare.png)
    - They are getting really close, but office prices are still higher
- Heatmap of Canada with current house prices for each available district
![House Price Heatmap](./charts/House%20Price%20Heatmap.png)
- Price difference between Montreal and Toronto
![Montreal vs Toronto](./charts/District%20Difference.png)
    - Montreal is still cheaper than Toronto, but the gap is closing
- Trend of house prices with monthly earnings
![House Price vs Earnings](./charts/House%20Price%20with%20Earning.png)
    - House prices are increasing faster than earnings
- Did people spend more of their earnings in 2014 than they did in 2001?
![Earning vs Spending](./charts/Earning%20vs%20Spending.png)
    - No, the percent of earnings spent decreased from 16% to 13% from 2001 to 2014
- Financial Crises
![Financial Crises](./charts/Financial%20Crises.png)
    - House prices dropped in 2008, but recovered quickly
    - Office prices dropped in 2008, but recovered slowly
    - Consumer index dropped in 2008, but recovered quickly
    - Earnings dropped in 2008, but recovered quickly
- Consumer Index vs House Prices
![Consumer Index vs House Prices](./charts/House%20Price%20vs%20Consumer%20Index.png)
![description](./charts/description.png)
    - Consumer index is a good indicator of house prices, as the R-squared value is around 0.854, which means this trend is applicable to 85.4% of the data.
### Bonus
- House Price Difference vs Earning Difference
![House Price Difference vs Earning Difference](./charts/House%20Price%20Difference%20vs%20Earning%20Difference.png)
    - The difference between house prices and earnings is increasing, but dropped below 0 in 2008

## Challenges 
- Understanding datasets
- Combining data
- Manipulating Tableau

## Future Goals
- Look at the dataset beforehand
- Play around with dataset in Tableau to see the trends

