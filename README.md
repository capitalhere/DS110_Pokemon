# DS110_Pokemon

Objective: To train the machine learning algorithm to be able to identify any Generation 1 Pokemon from a given image and return its stats (and name) back to the user.

Dataset of the original 151 Pokemon with stats only from Generation 1.
https://www.kaggle.com/datasets/dizzypanda/gen-1-pokemon

Dataset containing images of each Generation 1 Pokemon.
https://www.kaggle.com/datasets/thedagger/pokemon-generation-one

1st Approach
Random Forests will be one approach, as its efficiency in using multiple decision trees is attractive for training an image classifier.

2nd Approach
K-Nearest Neighbors will be another approach, given its simplicity. While it may not be the best for our purpose, a classifier using KNN could be compared with that using Random Forests to hopefully confirm and teach us that the latter is better.

In the 1st approach (random forests), there are many potential varying parameters, with some candidates being maximum depth and random state. This has yet to be decided. In the 2nd approach (KNN), K will be the varying parameter.


