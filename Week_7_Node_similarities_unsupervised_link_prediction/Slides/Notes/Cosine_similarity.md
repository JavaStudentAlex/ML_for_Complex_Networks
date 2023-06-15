#note #metric 

$$cosim(v, w) = cos(\alpha) = \frac{\vec{A}_v \vec{A}_w}{| \vec{A}_v| \times |\vec{A}_w|} \in [-1, 1]$$

This metrics uses columns of adjacency matrix as embeddings in $\mathcal{R} ^ V$ space. This metric is special because it can have probable links with value of similarity $[0, 1]$ and anti-probable links with values $[-1, 0)$. The second category are the links that means that nodes are counterparts. 