Once the data has been collected, there may be a huge difference bw the scales of the variables

this cause issues in various cases( KNN, PCA) related algos.

To overcome this feature scaling is done.

1. in standardization( z score normalization) 
mean=0 and SD=1

brings data in a range (99.7% values lie in (-3,3))

accuracy score improves upon logistic regression

2. In normalization, we need the min and max values of the column
   
data lies between [0,1]

3. Ordinal encoding: Done when we have a relationship bw data(ordinal data)

4. onehotencoding: Done when data is independent(can be done through pandas and seperately)
   
