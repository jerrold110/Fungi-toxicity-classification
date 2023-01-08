# Fungi specimen classification
(a) Mushroom records drawn from The Audubon Society Field Guide to North American Mushrooms (1981). G. H. Lincoff (Pres.), New York: Alfred A. Knopf

(b) Donor: Jeff Schlimmer (Jeffrey.Schlimmer@a.gp.cs.cmu.edu)

(c) Date: 27 April 1987

The purpose of this data mining project is to classify the edibility of fungi specimens based on 22 different physical characteristics. The dataset has over 8124 rows of data with 23 columns, each representing the physical data of a fungi specimen. This is an entirely categorical dataset with a binary class label: poisonous or edible - which poses some difficulties in training a machine learning model. About one quarter of the data has missing values which were estimated using data (it is not possible to take the mean/median from categorical data) from other rows rather than just simply being removed. Features were selcted for clearning and modelling by statistical analysis of the extent a feature accounts for class variance. Two types of classifier models were used and compared against each other to classify edibility: Decision trees and Random forest. Finally, the conclusions and suggestions for deployment are included in the last section of Data Modelling.

Data Understanding and Exploration:
* Exploratory analysis
* Visualisation analysis
* Feature selection

Data Cleaning and Preprocessing:
* Filling in missing values by searching for suitable predictors
* One hot encoding

Data Modelling:
* Model selection and justification
* Data model fitting
* Hyperparameter optimization
* Model assessment
