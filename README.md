# CookCountyData
This is an excerpt of an ongoing Cook County Assessors data. There is a dedicated data science team for working on this data in Cook County, Illinois (US). Their major task is to predict the house prices. One of the main tasks that they undertake is property valuation - an exercise that is critical to property taxation (a critical source of revenue for the local administration) and determination of fair land and housing prices (which influences the shape of economic development).

Since only a fraction of properties will be sold each year, you need to build a model that predicts the potential market price of any property from its factors such as its location, style, size, contents as well as external factors like the seasonal variation in demand, conditions of sale, etc.

Not only do you want a strong predictive model, but you also want an equally good explanatory model because property owners can contest the evaluation and even take the administration to court. So not only do you need to take safeguards to prevent the model from providing extreme valuations, but you also must be ready to identify and explain exactly what causes these variations. This is not a toy dataset but a real-world ongoing problem. So data is messy and sometimes erratic, but once processed the data makes sense and patterns hold stable.

## The Data
Original Data sources -
* 5 Years of Residential property assessment of single houses, apartments, and condominiums (essentially community living) by surveyors who map the size, location, quality and contents of the property.
* 5 Years of Housing sale data from legal deeds covering nearly 5 lakh transactions of property.
These two have been merged to form a single dataset, such that at the date of sale we now know the latest information regarding the house. This dataset has been split into a simulation and holdout dataset, you must use the simulation dataset to build your models and interpret. The holdout dataset, having been cleaned of outliers and uses only arms-length transactions, will be the final arbitration for your predictive model.
More details about this project can be found [here](https://gitlab.com/ccao-data-science---modeling/ccao_sf_cama_dev/-/tree/master).

## Notebook
My repo here will focus on two tasks basically, prediction and interpretation.
