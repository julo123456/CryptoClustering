# CryptoClustering
## This is a project task to perform Unsupervised Machine Learning
### Tools: Python 
### Unsupervised Machine Learning Methodology:
#### Step 0- Data Prep
Use the StandardScaler() module from scikit-learn to normalize the data
#### Step 1- K-Mean Clustering
A for loop to find the best KMean value followed by using Elbow curve to determin the best kMean; in addition to utilizeing the For-Loop, KMeans() function to get a model was conducted.
#### Step 2- Principal Component Analysis (CPA)
pca.fit_transform() function was utilized to compress normalized data from step 0 and only look at three PCAs. Also a For-Loop and Elbow Curve was generated to find the best KMean value, additioally KMeans() function to get a clustering model was conducted.
### Step 3- Comparion 
Contrast the Elbow Curves based on originally scaled data and PCA data.
Contrast the segmentation/clusters based on originally scaled data and PCA data.
