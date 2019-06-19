

```python
import pandas as pd
p=pd.DataFrame({'a':[1,2,3],'b':[4,5,6],'c':[7,8,9]})
p.values
```




    array([[1, 4, 7],
           [2, 5, 8],
           [3, 6, 9]], dtype=int64)




```python
import pandas as pd
a=pd.DataFrame({'a':[1,2,3],'b':[4,5,6],'c':[7,8,9]})
p.values
```




    array([[1, 4, 7],
           [2, 5, 8],
           [3, 6, 9]], dtype=int64)




```python

p                                                                 #To view the data as table form

```




<div>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>a</th>
      <th>b</th>
      <th>c</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>1</td>
      <td>4</td>
      <td>7</td>
    </tr>
    <tr>
      <th>1</th>
      <td>2</td>
      <td>5</td>
      <td>8</td>
    </tr>
    <tr>
      <th>2</th>
      <td>3</td>
      <td>6</td>
      <td>9</td>
    </tr>
  </tbody>
</table>
</div>




```python
p.a                        #To view the data of a particular element
```




    0    4
    1    5
    2    6
    Name: b, dtype: int64




```python
 p[['b','c']]               #To view the element for desired element 
```




<div>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>b</th>
      <th>c</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>4</td>
      <td>7</td>
    </tr>
    <tr>
      <th>1</th>
      <td>5</td>
      <td>8</td>
    </tr>
    <tr>
      <th>2</th>
      <td>6</td>
      <td>9</td>
    </tr>
  </tbody>
</table>
</div>




```python

```
