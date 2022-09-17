# Gaussian-Mixture-Model
	Project Flow:
  Part 1: Exploratory Data Analysis
  Part 2: Single feature with single GMM (n=1) 
  -> unsupervised learning for the best 3 distinguished feature(don't use the label and fit both non-fraudulent and fraudulent classes)
  -> supervised learning for the best 3 distinguished feature(use the label and fit only non-fraudulent  class)
  -> compare the AUC and ROC
  -> select the cut off to maximize the metrix (in this case F1 score) to make the prediction on fraudulent or not
	Part 3. Multi feature with single GMD (n>1 ) 
  -> Visualized the Scatter plot with two features and find the approximated n-components
  -> Unsupervised learning for two features in one Gaussian (n>1) (fit both non-fraudulent and fraudulent classes)
  -> select the cut off to maximize the metrix (in this case F1 score) to make the prediction on fraudulent or not
	Part4. Single feature with Two GMDs
  -> Supervise learning on non-fraudulent class
  -> Superivise learning fraudulent class
  -> Find the threshold to find the cutoff number 
Part5. Explore different combinations on n-components, # of features, # of GMDs 
