



```
import numpy as np
x=np.array([[1,2,3,4],[5,6,7,8],[8,9,10,11],[12,13,14,15],[16,17,18,19]])
x
```




    array([[ 1,  2,  3,  4],
           [ 5,  6,  7,  8],
           [ 8,  9, 10, 11],
           [12, 13, 14, 15],
           [16, 17, 18, 19]])




```
#Slicing COncept
#Lets slice out only the element ([2,3,4],[6,7,8])
x[0:2,1:4]
    
```




    array([[2, 3, 4],
           [6, 7, 8]])




```
#Lets slice out the element ([9,10,11],[13,14,15],[17,18,19])
x[2:5,1:4]
```




    array([[ 9, 10, 11],
           [13, 14, 15],
           [17, 18, 19]])




```
x
```




    array([[ 1,  2,  3,  4],
           [ 5,  6,  7,  8],
           [ 8,  9, 10, 11],
           [12, 13, 14, 15],
           [16, 17, 18, 19]])




```
#Lets slice out the element ([12,13,14],[16,17,18])
x[3:5,0:3]
```




    array([[12, 13, 14],
           [16, 17, 18]])




```
a=np.arange(0,25).reshape(5,5)
a
```




    array([[ 0,  1,  2,  3,  4],
           [ 5,  6,  7,  8,  9],
           [10, 11, 12, 13, 14],
           [15, 16, 17, 18, 19],
           [20, 21, 22, 23, 24]])




```
#Size of the Array
a.size
```




    25




```
#Sum of all the element given in the array 
a.sum()
```




    300




```
#Max of given element
a.max()
```




    24




```
#Min of the given element
a.min()
```




    0




```
#finding the mean of the element
a.mean()
```




    12.0




```
a.argmin()
```




    0




```
a.argmax()
```




    24




```
#argmax ---> max  and # argmin ---> min
#a.argmax() ---> #a.max() and #a.argmin()---> #a.min() 
```
