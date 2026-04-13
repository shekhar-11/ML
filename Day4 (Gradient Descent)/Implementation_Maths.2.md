

w = w - learning_rate * d/dw(J(w,b))            
b = b - learning_rate * d/db(J(w,b))            

note here its partial derivative


learning rate is alpha , determines how fast we want to reach the minimum point of cost function, if lr is too high then we may miss the min point of cf and if lr is too low then it will take time to reach the min pt.


No matter, what is the learning rate, we will reach the min. point , like if more slope then we will take big steps as high derivative value and so converse for low slope, so less steps as we reach near local minima , so it gets adjusted as we approach the minima point, so even at fixed learning rate we will reach the minima pt by different step sizes. 



FOR LINEAR REGRESSION:
its a convex function, so it has only one minima point --- so it will reach the global minima point itself.ss
