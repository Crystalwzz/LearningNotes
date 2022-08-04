# Machine Learning Notes
## Topic 1: Data Pre-processing and Visualization
### Missing data
Techniques: 
1. Omission
2. Imputation

Why? Reduce the probability of introducing bias, most ML algorithms require complete data

My imputation example:
Missing Data. The ELS:2002 study had missing data ranging from 3% to 30% due to survey item nonresponse. After examining the missing patterns, it was determined that missing occurred randomly. Since missing data can reduce sample size and potentially increase estimate bias, imputation was used as a strategy to replace missing values (Allison, 2005). More specifically, we used fully conditional specification algorithms for the imputation. <br/>
-- SAS mi resource: https://support.sas.com/resources/papers/proceedings15/2081-2015.pdf

### Data distributions and data transformation
1. different distribution in test and training datasets
2. transfer non-normal to close to normal  <br/>
  -2.1 box-cox transformation: https://www.statisticshowto.com/probability-and-statistics/normal-distributions/box-cox-transformation/  <br/>
       log and power transformations
       
### Data outlier and scaling
1. outlier <br/>
  1.1 inter-quartile range
2. scaling:
  2.1 standardization
  2.2 normalization
