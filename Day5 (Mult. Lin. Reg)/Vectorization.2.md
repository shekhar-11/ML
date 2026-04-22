in maths/linear algebra , we show 

y = w1*x1 + w2*x2 + ... + wn*xn + b
but in py --
y = w[0]*x[0] + w[1]*x[1] + ... + w[n-1]*x[n-1] + b


for i in range(0,n):
    y += w[i]*x[i]
y += b



vectorization is the process of converting the above for loop into a single line of code using numpy's dot product function

numpy is powerful lib for maths and linear algebra operations

y = np.dot(w,x) + b


this is fast(bts -- numpy is able to use parallel h/w ) and short



similarly if for gradient descent , 
we need ---

wi = wi - di/dw   (di  is the derivative of the cost function with respect to wi)

and for each i we need to find 

using vectorization we can find the gradient all at once ( as behind the scene numpy is using parallel computing making much faster output)


and at last for all wi 

w = w - learning_rate * gradient 

so for all 16(n) values are updated at once using vectorization and numpy's dot product function