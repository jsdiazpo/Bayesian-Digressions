```python
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
%matplotlib inline
# plt.rcParams['figure.facecolor'] = 'w'
plt.style.use('dark_background')
import seaborn as sns
import random
from scipy.special import beta as beta_function

d0 = np.array([1,1,1,1,1])
p0 = d0/sum(d0)
print(p0)

d1 = np.array([4,3,2,1,0])
p1 = d1/sum(d1)
print(p1)

d2 = np.array([0,1,2,3,4])
p2 = d1*d2/sum(d1*d2)
print(p2)

d3 = np.array([0,1,2,3,4])
p3 = d1*d2*d3/sum(d1*d2*d3)
print(p3)

d4 = np.array([0,1,2,3,4])
# d4 = np.array([4,3,2,1,0])
p4 = d1*d2*d3*d4/sum(d1*d2*d3*d4)
print(p4)
```
