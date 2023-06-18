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


From the histogram we can see that the binomial distribution can be approximated by a normal distribution, even though it is discrete and the normal is continuous. Assuming that n is large, the probability (or frequency, as we have here) of the binomal taking different values will mimic a normal distribution, assuming a p close to 0.5.