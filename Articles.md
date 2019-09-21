# Interesing Articles

## Dropout

	- Dropout:  A Simple Way to Prevent Neural Networks from Overfitting (Srivastava, 2014) 
		(classic) 
<span></span>

	- Dropout as a Low-Rank Regularizer for Matrix Factorization (Vidal, 2017)  (https://arxiv.org/pdf/1710.05092.pdf)
		A theoretical analysis of dropout for matrix factorization. 
		Proved that the expectation computed over r1,...,rd∼Bernoulli(θ) casts dropout into the a fully deterministic optimization problem.
		Connections btw Dropout and nuclear norms
<span></span>
	
	- On the Implicit Bias of Dropout (Vidal, 2018) (link)[https://arxiv.org/pdf/1806.09777.pdf]
		They show that dropout prefers solutions with minimal path regularization. 
		Even if dealing non-convex optimization problem, they fully characterize the global optima of the dropout objective.
		Show dropout favors low-rank weight matrices that are equalized. 
		Confirms dropout as a procedure uniformly allocates weights to different subnetworks, preventing co-adaptation.
		They characterize the optimization landscape of learning autoencoders with dropout.
		All localoptima are equalized.
		For sufficiently small dropout rates,  there are no spurious local minimain the landscape, and all saddle points are non-degenerate.
		Suggest that dropout can efficiently converge to a globally optimal solution 
<span></span>
		
	- On Dropout and Nuclear Norm Regularization (Mianjy, Arora, 2019) (https://arxiv.org/pdf/1905.11887.pdf)
		
		Derives  the explicit  regularizer induced by dropout, composed of the 2-path regularizer and other rescaling invariant regularizers. 
		The convex envelope of the induced regularizer factors into an effective regularization term and and a term strictly related to Nuclear norms.
		Further highlight equalization as a key network property under which the induced regularizer equals its convex envelope.  
<span></span>


		
