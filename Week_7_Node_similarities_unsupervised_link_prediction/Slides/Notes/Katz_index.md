#note #metric 

$$K(v, w) = \sum_{k=1}^{\infty} \beta^k |A_{v,w}^k|$$

The Katz index free us from choosing maximum length of walks. And with $\beta \in [0,1]$ we controll the importance of each length. In matrix form the infinite series converges to:
In matrix form:

$$K = (I - \beta A)^{-1} - I$$

, where I is the identity matrix(matrix with $\vec{1}$ diagonal and 0 for all other elements) with size $n \times n$.
But this metric does not incorporate node degrees.