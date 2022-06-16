# Antarctica Classifcation

These are the codes used to classify the landscape of Antarctica in Google Earth Engine (JavaScript)

These scripts can be broadly split into two components: i) Land Classification; ii) Accuracy Assessmment. I have split these into branches.

# 1) Land Classification

Part 1: This step topographically corrects selected images

Part 2: This step runs a PCA over the images and clusters them into the desrired number of clusters

Part 3: This is the script used in the limited times where a random forest was required

# 2) Accuracy Assessment

Part 1: This counts the number of pixels of each land type. This allowed us to calcualte the number of points to sample (stratified sampling)

Part 2: This creates the sampling points

Part 3: This allows you to go to inspect the image at each accuracy point

Part 4: This creates a grid and counts the number of accurate and inaccurate points, for the spatially mapped accuracy assessment map
