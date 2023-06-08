#note #entropy 

The average description length of a single step is:

$$L(M) = q H(Q) + \sum_{i = 1}^{m} p H(P)$$

, where:
- q - probability that random walker switches modules
- H(Q) - entropy of the modules names
- p - fraction of within module movements joined with probabulity to exit module 
	$\sum_{i=1}^{m} p_i = 1 + q$ 
- H(P) - entropy of inline module coding sytem
