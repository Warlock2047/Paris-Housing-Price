# Paris Housing Price
## Promotion Of the Project
1. square meters: square meter of the house
2. number of rooms: number of rooms in the house
3. has yard: whether the house has a courtyard
4. has pool: whether the house has a pool
5. floors: how many floors does the house have
6. city code: postal code of the city
7. city part range: the privilege of the distance from the city
8. num prev owners: how many people previously owned the house
9. made: What year was the house built
10. is new built: whether there is a new building
11. has storm protector: whether there is a storm protector at home
12. basement: basement floor area
13. attic: attic square meter
14. garage: garage square meter
15. has storage room: whether there is a storage room
16. has guest room: whether there is a guest room
17. price: house price 

# REPORT 

1. Our aim in this project is to analyze the house sales prices according to the basis that people living in Paris pay attention to when buying a house.
2. In this project, we want to see which houses people living in Paris prefer and the features they look for when buying a house. People have various preferences when buying a house. While these criteria may be the presence of a pool, multi-storey, what year it was built, for some people, it may be that the material was used in a house farther from the city.
We also want to see which criteria are effective in people's home purchases and carry out a study accordingly. In this project, we aim to see which houses people living in Paris prefer and the features they look for when buying a house. Our data is an imaginary dataset of housing prices in Paris. As a result of the data analysis we have done, we aim to find the most appropriate regression model by testing the data set we have trained with more than one regression model for the data set.
3. In the project, analysis was started after we got to know our data for the first time. We examined the relationships between the variables in the data and used many different charts for various visualization options. In order to better understand the data, multiple graphs such as box plot, scatter plot, join plot, histogram, bar plot, line plot were used.
4. These graphs, which are part of our dataset analysis, are violin plot and bar plot. When we look at the graphics, the privilege of the distance from the city did not cause a change in the price. We see that the distance from the city is not an important criterion for a change in the price of people when buying a house.
5. In these charts, we look at whether homes have storm protection, depending on the distance from the city. We see that the distance from the city has no effect on whether there is a storm guard or not. There is no significant difference between the number of houses with storm protection and those without.
6: In the graph, we see the relationship between the sale price of the house and the square meter of the house. We can say that there is a linear relationship between the sale price of the house and the square meter of the house. In other words, as the square meter of the house increases, the selling price of the house also increases.
7. As a result, if we look at the results of the regression models that we have applied
8. If we make inferences for linear regression, when we look at the R-Square value, we see that our model is very close 9. If we infer for Ridge, Lasso and KNeighbors, Random Forest, Artificial Network regressions, we observe that those regression models are also good models too.
10. If we infer for Elastic Net regression, this regression model is not a model that gives us good results when we look at our values. The mean squared error is also very high.
11. Support Vector Regressor model is absolutely unusable.
12. When we look at the graphics, we prefer the models that give the highest performance and have the lowest errors in our models. As perfromans, we see that Linear Regression, Ridge Regression, Lasso Regression, Random Forest Regressor and Arificial Neural Networks models are the best. However, the KNeighbors Regressor is also a usable model, but it will not be our first choice. Our models with the lowest error among all models are Linear, Lasso Regression and Artificial Neural Networks models.

- [Data Set](https://www.kaggle.com/datasets/mssmartypants/paris-housing-price-prediction)
