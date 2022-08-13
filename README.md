# Used_Cars Dataset Exploration

## by Gbenga Olurankinse


## Dataset

The dataset consist of 7906 informations of Used Cars in USA on each 18 features which include selling price of the used car, maximum power, engine, transmission, owner, seller type, purchase year, name(brand of the car), mileage, km driven amongst others.  <br>
The dataset can be found [here](https://www.kaggle.com/datasets/shubham1kumar/usedcar-data/code?select=UserCarData.csv)
for direct download, click [here](https://www.kaggle.com/datasets/shubham1kumar/usedcar-data/download?datasetVersionNumber=2)

The preminary wrangling performed on the dataset before exploration are:
1. changed all the column names to lower case
2. extracted first word from owner observations
3. removed rows with Test observations
4. dropped sales_id, torque,sold column
5. group year and convert year, seats, owner to ordinal category. brand, region, state, fuel, seller_type, transmission and city to nominal category


## Summary of Findings

In the exploration, I found out that most of the selling price of the used car, distance driven in km, and maximum power of the used cars are of low values. Also majority of the car were 7 seaters, manual transmission, uses diesle or petrol, owned by first owner, and purchase in year bewteen 2010-2019.
Later in the course of the exploration I discovered that selling price is positively strongly correlated with maximum power of the car as increase in one leads to increase in the other.
I also found the strong correlation between selling price and purchase year of the used car. In addition, there was also a strong correlation between the selling price and the Transmission also between purchase year and owner.


## Key Insights for Presentation

For the presentation, I focused mainly on the effects of Maximum Power, Purchase Year and Transmission on the Selling Price of the used cars. I started by plotting the distribution of the Selling Price using log transformation scale.

I moved on to see plot log transformation of selling price against maximum power using scatterplot so as to see the effect of used car maximum power on the selling price. 

To see the effect of Purchase Year on selling price, I used boxplot to plot the selling price on log scale against normal purchase year and selliing price increases as the year of purchase becomes recent.

I also plot transmission against selling price on log scale and it was seen that manual cars are more cheaper than automatic cars.

I went see the relationship between Selling Price of Used Cars and Maximum Power Across Purchase Year using scatterplot, this proves that purchase year of a car with maximum power can be used to predict the selling price of a used car.

Finally, I plot using a pointplot to see the relationship between  Selling Price of Used Cars and Purchase Year Across Transmission
it was established that the average selling price of automatic cars across the year is always higher than the average selling price of manual used cars.