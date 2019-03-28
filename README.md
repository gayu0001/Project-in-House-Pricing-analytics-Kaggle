# Project-in-House-Pricing-analytics-Kaggle
Appendix

The following table illustrates all the accompanying Files and their respective purposes:
The R Codes are splitted into several files to speed up our processing. Hence, it is recommended to run these R Codes (in Notebook format) in the following sequence. For ease of reference, R Markdown docs (in HTML) are also enclosed in the submission.
S/N	Category	Filename	Purpose	Input File	Output File
1	R Codes 	data_preparation.Rmd	Data Preparation		all_DP.rds
	R Codes 	analytics.Rmd	Data Analysis	all_DP.rds	
2	R Codes 	feature_engineering.Rmd	Feature Engineering	all_DP.rds	all_DP_FE.rds
3	R Codes 	Pre_Processing.Rmd	Data Pre Processing 	all_DP_FE.rds	train.rds
test.rds
4	R Codes 	regularized regression.Rmd	Regularized Regression
(cover both Ridge and Lasso)	train.rds
test.rds	ridge-sol.csv
5	R Codes 	random_forest.Rmd	Random Forest	train.rds
test.rds	
6	R Codes 	xgboost.nrounds1000.Rmd	XGBoost where nrounds = 1000
(long CPU Processing)	train.rds
test.rds	
7	R Codes 	xgboost.nrounds10.10.Rmd	XGBoost where nrounds = 10	train.rds
test.rds	
8	Additional R packages:	library(knitr)
library(ggplot2)
library(plyr)
library(dplyr)
library(corrplot)
library(caret)
library(gridExtra)
library(scales)
library(Rmisc)
library(ggrepel)
library(rand omForest)
library(psych)
library(xgboost)
library(moments)
library(glmnet)
library(elasticnet)
library(Metrics)	To run above R Codes, 
load this list of Additional R packages (besides base R)
		
8	R Markdown docs (in HTML)	*.html	To preview our R outputs (for each of the R Codes)		
9	Data	train.csv	Training Dataset		
10	Data	test.csv	Testing Dataset		
11	Data	data_description.txt	Data - description file		
 
