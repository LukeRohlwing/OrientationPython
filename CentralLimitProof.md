# Proof of Central Limit Theorem

```python
import numpy
from matplotlib.pyplot import plt
binomial = numpy.random.binomial(100, 0.5, size = 10000)
plt.hist(binomial, bins = 14)
plt.show()
```

```{r,engine='python'}
import numpy
from matplotlib.pyplot import plt
binomial = numpy.random.binomial(100, 0.5, size = 10000)
plt.hist(binomial, bins = 14)
plt.show()
fig.savefig('foo.png', bbox_inches='tight')
print "finished"
```
Output image:
![output](foo.png)
