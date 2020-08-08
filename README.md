# Data-science--cipher-school-assignment
This repository contains  an EDA, and observations on Haberman's Survival Data Set (Survival of patients who had undergone surgery for breast cancer).

#Objective

To predict whether the patient will survive after 5 years or not based upon the patient's age, year of treatment and the number of positive lymph nodes.

#High level statistics of the dataset

In this section, we have desctribed number of points, number of features, number of classes, data-points per class.

#Uni-variate analysis

Univariate analysis is the simplest form of analyzing data. “Uni” means “one”, so in other words your data has only one variable. It doesn't deal with causes or relationships (unlike regression ) and it's major purpose is to describe; It takes data, summarizes that data and finds patterns in the data.
We have plotted PDF, CDF, Boxplot, Violin plots to understand which features are useful towards classification, in this part.

#Bi-variate plots

Bivariate analysis is the analysis of exactly two variables.
We have plotted scatter plots, pair-plots to see if combinations of features are useful in classification, in this section

#Observation

There are no missing values in this dataset. So there is no need to do data imputation.
The datatype of 'survival_status_after_5_years' column is integer. It has to be converted to categorical datatype.
The values of 'survival_status_after_5_years' column are not meanigful. Hence they are mapped to 'yes' (survived after 5 years) and 'no' (not survived after 5 years)

