# Classification - ML

## 1.1 PROJECT SCOPE

The scope of the project is to predict and categorize whether a consumer will cancel a reservation or not. 
The machine learning method was used for this project. 
This is accomplished by data preparation, Spatial Analysis, encoding, EDA, splitting the data collection, and model building. 

Python is used in this project for the visualization. 
We concluded data about the price per night, peak visitor months, average length of stay, and other factors.
In order to determine which algorithms are the best, we also have an automated model.



## 1.2 BRIEF DISCUSSION

We must import the necessary libraries first. To grasp the data better, we must outlook it.


### Data pre-processing

We replace missing values at the crucial phase of data pre-processing.

### Analysis

One of the key components of finding insight is analysis.
Since adults, infants, and children can't all be zero at once, there is some dirtiness in the data.
Using geographical analysis, we were able to determine the origin of the visitors.
The bulk of the visitors, according to our study, come from Portugal and other European countries.
We discovered a correlation between the price per night and how much guests pay for a room each night.

### Co-relation

Important features using Machine learning
The quantity of booking modifications, however, is a potential source of leakage when attempting to forecast whether or not a reservation will be cancelled because this data might alter over time.

### Handle Outliers

Important since they have the potential to alter the outcome of our investigation, which we have also viewed using several plots

### Feature Importance

We utilize the importance score in the feature Importance (total features, selected features)
A list of the features we've chosen can be created.

### Splitting dataset & building model

Here, we employ a variety of algorithms, including Random Forest and Logistic Regression.
We train, test, and partition the data using machine learning algorithms to determine which model's "Accuracy of the model" is the best.

### Cross-validating & Automated Algorithms

We are now cross-validating the model using train and test data.
The process is automated, and many algorithms are used to choose the best model and determine the accuracy score.



## 1.3 PROJECT GOAL

The project's goal is to use historical data to group different kinds of travellers who book accommodations at hotels and resorts.
Through a variety of algorithms, we can determine the best one to employ in determining if a consumer will book or cancel a room, Guests pay for a room per night.

We can also determine which season or month and which country have the highest customer ratios.
The project's outcome allowed us to predict if a room will be reserved or cancelled using a flawless model.
