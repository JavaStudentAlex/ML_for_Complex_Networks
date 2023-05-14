#theorem 

There is the set of nodes and each time stamp the new edge is added with equal probabilities. We will do it till the graph is completely connected. Let us denote $v_n$ as the number of edges in the resulted connected components. Then:

$$P(v_n = \left[\frac{1}{2} n log(n) \right] + l) \sim \frac{2}{n} e^{-\frac{2l}{n} - e^{-\frac{2l}{n}}}$$
for $|l| = O(n)$ and 

$$lim_{n \to \infty} P \left( \frac{v_n - \frac{1}{2}n log(n)}{n} < x \right) = e^{-e^{-2x}}$$
