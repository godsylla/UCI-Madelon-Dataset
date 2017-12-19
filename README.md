# UCI Madelon Dataset: Feature Selection + Classification

### Data
Demonstrate a capacity to identify relevant features using machine learning. 
[Madelon](https://archive.ics.uci.edu/ml/datasets/Madelon).
"MADELON is an artificial dataset containing data points grouped in 32 clusters placed on the vertices of a five dimensional hypercube and randomly labeled +1 or -1. The five dimensions constitute 5 informative features. 15 linear combinations of those features were added to form a set of 20 (redundant) informative features. Based on those 20 features one must separate the examples into the 2 classes (corresponding to the +-1 labels). We added a number of distractor feature called 'probes' having no predictive power. The order of the features and patterns were randomized." 

The Madelon Dataset does not have attribute information to avoid biasing feature selection.

MADELON -- Positive ex. -- Negative ex. -- Total	
- Training set -- 1000 -- 1000 -- 2000	
- Validation set -- 300 -- 300 -- 600	
- Test set -- 900 -- 900 -- 1800	
- All -- 2200 -- 2200 -- 4400	

Number of variables/features/attributes: 
Real: 20 
Probes: 480 
Total: 500 

### Problem Statement

Your challenge here is to develop a series of models for two purposes:

1. for the purposes of identifying relevant features. 
2. for the purposes of generating predictions from the model. 

#### Content
#### Data Sampling

Do substantive work on at least six subsets of the data. 

- 3 sets of 10% of the data from the UCI Madelon set
- 3 sets of 10% of the data from the Madelon set made available by your instructors


##### EDA 

- perform EDA on each set as you see necessary

##### Benchmarking
- Perform a naive fit for each of the base model classes:
	- logistic regression
	- decision tree
	- k nearest neighbors
	- support vector classifier

##### Identify Features & Feature Importance
- Considering these results, build a final predictive model
- Approaches:
    - Use feature selection to reduce the dataset to a manageable size then use conventional methods
    - Use an iterative model training method to find relevant features (ANOVA)
   
##### Build Model
- Implement final model

##### Additional Items to Add (forthcoming):
- ROC visualizations
- comparative score visualizations for different classification pipelines
- tune hyperparameters to improve accuracy/precision/recall and reduce logloss
