# Demand-Prediction
## Problem Description
Catapult Inc. is one of the leading pharma companies in the world. Their biggest clinical success over the last decade is due to docstar1000 which is an experimental spray aimed at quick healing of achilees heel. It was released in Austria, Canada, Germany, France, India, japan, USA and UK. A key ingredient to the production of this drug is the chemical "cycloxyflovin". The sprays are produced in the individual markets however, the chemical cycloxyflovin is manufactured in the company headquarters in Phoenix, USA and sourced to individual markets. The chemical cycloxyflovin is sourced to three different manufacturing centers in each of these countries periodically and each spray contains 1 unit (5mg) of cycloxyflovin

Catapult. Inc is planning the production process for the chemical cycloxyflovin for the upcoming cycle. Catapult.Inc has given us regionl demand estimates and global Sales for the past period. Now, given these demand estimates and global sales of the past period, we need to build a demand prediction model for the global sales of docstar1000

Additionally, Due to trade marketing regulation changes that took place over the last few years in the regions of Austria, Canada, Germany, France, India, japan and USA, the HQ at phoenix estimates that the demands of the spray docstar1000 were higher than what is reported in the dataset. For this purpose, they have given us a dataset that contains scaling factor that must be applied to the demand of the countries' respective production centres

## Data
You are given 2 datasets, one with estimated demand at the 3 production centres in each country and the total predicted demand. The second dataset contains the scaling factor per each country.

### Data Set 1
The data consists of 25 columns. The 8 countries and demand estimates of each of the processing centres in these countries and a seasonal scaling factor (Pharmacies in these regions tend to have periodic buying cycles. Additionally, achilees heel injury being predominantly sport induced, the pharmacies expect a surge in demand in certain times of the year more than the other)

### Data Set 2
Scaling factor to be applied to the countries

## Technical Environment
Python
numpy
pandas
scikit-learn
matplotlib / searborn / altair / plotly
## Approach
The solution is assessed on the following skills:

A thorough evaluation of the data set using statistical measures and visualization
Elegant Python coding skills
Machine Learning modelling fundamentals
Machine Learning Training
Model Evaluation
