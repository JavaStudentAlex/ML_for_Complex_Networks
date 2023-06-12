#note #algorithm

With this algorithm we use the same greedy algorithm but with chance to make an exploration. We take the probability to make steps whatever which results they give:

$$p(t) = e^{- \frac{I - \hat{I}}{t}}$$

, where 
- $I$ - old value
- $\hat{I}$ - new value
- t  - temprerature, it changes in time with formula:

$$t_i = \frac{1 + c}{1 + i + c}$$

, where c is the cooling slowness.
The algorithm in code:

```python
for i in range(iterations):
	t = (1 + c) / (1 + c + i)
	old_z = z[v]
	old_L = L(z)
	z[v] = random.randint(B)
	p = np.exp(-(old_L - L(z) / t))
	if L(z) < old_L or rand() > p:
		z[v]
```

