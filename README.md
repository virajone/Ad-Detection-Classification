# Summary
A learning model based on Random Forest classifers to detect Ads on web paegs. 
Methods Used : 
Data Imputation - MICE
Model Selection - K Fold
Hyperparamter Tuning - GridSearch
Parameters -  Max Depth
              N Features to Select
              Min. Samples Leaf


# Ad-Detection-Classification
The dataset has been provided by the **UCI Machine Learning Repository**. As per the data description provided, given below are some notable interesting points regarding the dataset : * The last column in every instance provides a label for the instance * The first 3 columns (continuous attributes) provide the height, width and aspect ratio for the ad frame * -28% data is missing for each continuous attribute * Column number 3 to 1557 are u.r.l+term(n) * Number of Instances: 3279 * Number of Attributes: 1558 * The features encode the geometry of the image (if available) as well as phrases occuring in the URL, the image's URL and alt text, the anchor text, and words occuring near the anchor text.
