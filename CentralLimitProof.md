# Proof of Central Limit Theorem

```python
import numpy
from matplotlib.pyplot import plt
binomial = numpy.random.binomial(100, 0.5, size = 10000)
plt.hist(binomial, bins = 14)
fig.savefig('histogram.png')
plt.show()
```
Output image:
![output](histogram.png)
