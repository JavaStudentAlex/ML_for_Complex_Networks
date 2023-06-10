#note #G_n_p #likelihood

$$
\begin{align*}
\mathcal{L}(\Theta | G) &= P(G | \Theta) = \\
&= P(G) = \\
&= p^m (1 - p)^{\binom{n}{2} - m} \\

log \mathcal{L}(\Theta) &= m \log p - \left( \binom{n}{2} - m \right) \log (1 - p) \\
\frac{\partial{\mathcal{L}}}{\partial{p}} &= \frac{m}{p} - \frac{\binom{n}{2} - m}{1 - p} = 0 \\
\frac{m}{p} &= \frac{\binom{n}{2} - m}{1 - p} \\
m - mp &= p \binom{n}{2} - mp \\
p &= \frac{m}{\binom{n}{2}}
\end{align*}
$$
