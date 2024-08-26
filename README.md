# DecisionTree
This is a Decision Tree for optical-digit classification. 
Train the Decision Tree using the optdigits train.txt data, 
tune the minimum node entropy using optdigits valid.txt data, 
and test the prediction performance using the optdigits test.txt data. 
For each file, the first 64 columns correspond to the binary features for different samples while the last one stores the labels. 
The minimum node entropy is used as a threshold to stop splitting the tree, and set the node as a leaf.
