# DS110_Pokemon

Objective: To train the machine learning algorithm to be able to identify any Generation 1 Pokemon from a given image and return its stats (and name) back to the user.

Template: 2
Publicly available datasets to be used
Dataset of the original 151 Pokemon with stats only from Generation 1.
https://www.kaggle.com/datasets/dizzypanda/gen-1-pokemon
Download Link: Pokemon Stats         

Dataset containing images of each Generation 1 Pokemon. The image count of a single Pokemon ranges from 41 to 298, with 10,000+ in total. Each Pokemon is contained in a separate folder (totalling 149 folders). https://www.kaggle.com/datasets/thedagger/pokemon-generation-one
Download Link: Pokemon Images

1st Approach
Random Forests will be one approach, as its efficiency in using multiple decision trees is attractive for training an image classifier.

2nd Approach
K-Nearest Neighbors will be another approach, given its simplicity. While it may not be the best for our purpose, a classifier using KNN could be compared with that using Random Forests to hopefully confirm and teach us that the latter is better.

Columns used for prediction
An image database will be used for prediction. 

Our plan for varying parameters in our approach 
In the 1st approach (random forests), there are many potential varying parameters, with some candidates being maximum depth and random state. This has yet to be decided.
In the 2nd approach (KNN), K will be the varying parameter.


