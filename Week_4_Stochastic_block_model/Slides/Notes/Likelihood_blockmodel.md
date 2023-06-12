#note #blockmodel #likelihood 

$$
\begin{align*}
\mathcal{L} &= P(G) = \\
&= M_{kl}^{E_{kl}} (1 - M_{kl})^{N_{kl} - E_{kl}} \\
\updownarrow \\
\log \mathcal{L} &= E_{kl} \log M_{kl} + (N_{kl} - E_{kl}) (1 - M_{kl}) \\
\updownarrow \\
\frac{\partial \log \mathcal{L}}{\partial M_{kl}} &= \frac{E_{kl}}{M_{kl}} - \frac{N_{kl} - E_{kl}}{1 - M_{kl}} = 0 \\
\updownarrow \\
M_{kl} &= \frac{E_{kl}}{N_{kl}}
\end{align*}
$$
