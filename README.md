# K-Nearest Neighbor Algorithm on GPU 

In Classification Problems using Machine Learning, a dataset may have multiple classes but their sizes could be in different ratio. 
For example, let’s assume a dataset where we are trying to classify a student into 3 categories:
i.	“Good”, 
ii.	“Better”
iii.	“Best”

If the training set has many rows for the categories “Good” and “Better” but only few rows which belong to category “Best”, then this problem becomes a class imbalance problem in machine learning

A model trained on this imbalanced dataset will only be able to learn “Good” and “Better” classes perfectly but will lack learning the class “Best” significantly. 
Hence, the predictions also will only belong to classes “Good” and “Better” and will not have “Best” Category. To solve this, I use SMOTE: Synthetic Minority Oversampling TEchnique

SMOTE - It is a technique to create more data samples for the minority classes which is in this case “BEST” class. It will synthesize more data points in the dataset which belongs to the minority class making sure that the dataset have rows which have equal proportion of the classes

