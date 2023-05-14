#note 

[[Conn_graphs_gen_series_C(n,L)]]

Lets define $C_{N, L}$ as the number of connected random graphs. Each graph has the probability 
$$p^L q^{\binom{N}{2} - L}$$
to be connected. So The probability $P_n$ to get the connected graph is
$$P_n = \sum_{L} C_{N, L} p^L q^{\binom{N}{2} - L}$$
Based on the formula for the general case
$$\sum_{N, L} C_{N, L} \frac{x^N y^L}{N!} = log(1 + \sum_{i=1}^{\infty} \frac{x^i (1 + y)^{\binom{i}{2}}}{i!})$$
we can make a formula for the $P_n$
$$\sum_{n=1}^{\infty} P_n \frac{x^N q^{-\binom{N}{2}}}{N!} = log(1 + \sum_{i=1}^{\infty} \frac{x^i q^{-\binom{i}{2}}}{i!})$$
Both last series are convergent.

