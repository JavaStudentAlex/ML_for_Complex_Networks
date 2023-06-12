#note #blockmodel 

The microstate probability of the blockmodel is:
$$P(G) = \prod_{0 \leq k \leq l \leq B -1} M_{kl}^{E_{kl}} (1 - M_{kl})^{N_{kl} - E_{kl}}$$
, where:
- $E_{kl}$ - number of links between blocks
$$E_{kl} = |\{ (i, j) \in E : z_i = k and z_j = l \}|$$
- $N_{kl}$ - number of possible links between blocks k and l
$$N_{kl} = 
\left\{
	\begin{array}{ll}
		\binom{C_k}{2}  & \mbox{if } k = l \\
		C_k \times C_l & \mbox{if } k \neq l
	\end{array}
\right.$$
- $C_k$ - number of nodes in blocks
$$C_k = |\{ i \in V : z_i = k \}|$$
