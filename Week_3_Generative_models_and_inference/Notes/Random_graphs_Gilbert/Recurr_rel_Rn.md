#note 

The recurrent formula describes $R_n$
$$1 - R_n = \sum_{k=1}^{N - 1} \binom{N - 2}{k - 1} P_k q^{k(N - k)}$$
The k-th sum element is the probability that point 1 connects to exactly k - 1 from N - 2 other points. The whole sum is the probability that points 1 and 2 are not connected.