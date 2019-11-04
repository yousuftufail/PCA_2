# PCA_2

# An application of PCA (Principle Component Analysis)

Two datasets (Ex.1 grains dataset, 2-D) and (Ex. 2 fish dataset 6D) are considered.

In fitst example I have plotted the arrow (principle vector, basis in mathematical sense) that indicates the direction of scatter plott.

In second example, I have taken fish dataset (6-D) and Make a plot of the variances of the PCA features to find out which dimension is 
important and which dimenssion can be neglected. In this example I have also standarized the data because features have strong variation.
I have found that 2-dimenssionas are enough to represent this data.
At the end PCA is fit to the fish data with two components and generate the scattered plot. All four species can be seen in this scatter plot.

# Following python modules are required.

1. pandas
2. matplotlib.pyplot
3. pearsonr from scipy.stats
4. PCA from sklearn.decomposition
5. StandardScaler from sklearn.preprocessing 
6. make_pipeline from sklearn.pipeline  
