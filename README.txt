 * All changes should be made within the .ipynb file *

 * All images must be binary segmented images where the centrioles are white *

 * All images must be .tif files *

'variableNames' is used to identify images to be used. Only images that start one of the strings within variableNames will be processed in the analysis.

For each of the three functions, there are three inputs to be set. The first string dictates whether the function will be run. It can be set to 'true' to run or 'false' to not run. The second string is the file path or folder path of the images to be used. The third string is the output path where data will be saved.

'xaxis' represents the number of nearest neighbors calculated to within the variation and distance functions.

'centriolesInput' calculates the average number of centrioles in each category specified within 'variableNames'

'variationInput' calculates the coefficient of variation for centriole distance as a function of the number of nearest neighbors 

'distanceInput' calculates the average distance between centrioles as a function of the number of nearest neighbors