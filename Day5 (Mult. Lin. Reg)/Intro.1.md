so here we have the vectors of the features and the target variable

secondly , the weights are also the vector , and so , it is finally the dot product of the weights and the features that gives us the predicted value


formula is---
y = w1*x1 + w2*x2 + ... + wn*xn
in terms of vectors---
y = w . x



denoting --
x^i means the vector of features for the i-th data point , ie the ith row of the feature matrix X
xj means the vector of the j-th feature across all data points , ie the j-th column of the feature matrix X


so x^i is the ith row while the xj is the jth column of the feature matrix X

note xj = x subscript j and x^i = x superscript i


eg---

no. of bedrooms     no. of bathrooms     size in sqft     price
3                   2                   2000            500000
4                   3                   3000            750000      


so here x^1 is the vector of features for the first data point which is [3, 2, 2000] and x^2 is the vector of features for the second data point which is [4, 3, 3000]

and x1 is the vector of the first feature across all data points which is [3, 4] , x2 is the vector of the second feature across all data points which is [2, 3] and x3 is the vector of the third feature across all data points which is [2000, 3000]

and so x2(^1) means the value of the second feature for the first data point, which is 2



so the expression is --

y = x1w1 + x2w2 + x3w3 ..... + xnwn + b


b is the bias term 


eg === x1 is for no. of bedrooms , so for every unit of bedroom we have increase in price by w1, similarly for every unit of bathroom we have increase in price by w2 and for every unit of size in sqft we have increase in price by w3

and if we have years , and consider the negative coefficient for years, then we have decrease in price by w4 for every unit of year