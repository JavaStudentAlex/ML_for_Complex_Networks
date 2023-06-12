#note #algorithm

With this algorithm we randomly change some block and then check if it maximizes result. We can get stuck in local maxima.
```python
for i in range(iterations):
	old_z = z[v]
	old_L = L(z)
	z[v] = random.randint(B)
	if L(z) < old_L:
	z[v] = old_z
```
