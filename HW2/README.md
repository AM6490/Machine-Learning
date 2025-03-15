HW2 focuses primarily on experimenting with supervised learning models

Part A:

The objective in this section is to analyze how different variables affect test scores at a variety of school districts in California

This involved first getting an understanding of the data by plotting scatterplots and histograms. 
This allowed me to see how the target feature interacted with the other features. 

After this, I experimented with a variety of different supervised learning models to see which one performed the best:
1. Linear Regression
2. Lasso and Ridge
3. K-Nearest Neighbors

Variations of these models with cross-validation and StandardScaler() were ran as well. 

I found that the Lasso regression without StandardScaler() performed the best, with a test score of 0.81 and a cross-validation score of 0.783.

