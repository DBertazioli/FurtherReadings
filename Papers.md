# Interesing Papers

## Generals

	-Mathematics  of  Deep  Learning (Vidal, 2017)  
		global optimality, geometric stability, and invariance of the learned representations.
[link](https://arxiv.org/pdf/1712.04741.pdf)

## Generalization and Overparam

	- Reconciling modern machine learning practice and the bias-variance trade-off (Belkin, 2019)
		Double U curve (gen. error vs complexity)
[link](http://www.cs.columbia.edu/~djhsu/papers/biasvariance-pnas.pdf)

	- Learning and Generalization in Overparameterized Neural Networks, Going Beyond Two Layers (Allen-Zhu, 2018)
		(just an example of a series of articles, quite tough maths)
[link](https://arxiv.org/pdf/1811.04918.pdf)		

## Dropout

	- Dropout:  A Simple Way to Prevent Neural Networks from Overfitting (Srivastava, 2014) 
		(classic) 
<span></span>

	- Dropout as a Low-Rank Regularizer for Matrix Factorization (Vidal, 2017)  
		A theoretical analysis of dropout for matrix factorization. 
		Proved that the expectation computed over r1,...,rd∼Bernoulli(θ) casts dropout into the a fully deterministic optimization problem.
		Connections btw Dropout and nuclear 
[link](https://arxiv.org/pdf/1710.05092.pdf)
	
	- On the Implicit Bias of Dropout (Vidal, 2018) 
		They show that dropout prefers solutions with minimal path regularization. 
		Even if dealing non-convex optimization problem, they fully characterize the global optima of the dropout objective.
		Show dropout favors low-rank weight matrices that are equalized. 
		Confirms dropout as a procedure uniformly allocates weights to different subnetworks, preventing co-adaptation.
		They characterize the optimization landscape of learning autoencoders with dropout.
		All localoptima are equalized.
		For sufficiently small dropout rates,  there are no spurious local minimain the landscape, and all saddle points are non-degenerate.
		Suggest that dropout can efficiently converge to a globally optimal solution 
[link](https://arxiv.org/pdf/1806.09777.pdf)

		
	- On Dropout and Nuclear Norm Regularization (Mianjy, Arora, 2019) 
		
		Derives  the explicit  regularizer induced by dropout, composed of the 2-path regularizer and other rescaling invariant regularizers. 
		The convex envelope of the induced regularizer factors into an effective regularization term and and a term strictly related to Nuclear norms.
		Further highlight equalization as a key network property under which the induced regularizer equals its convex envelope.  
[link](https://arxiv.org/pdf/1905.11887.pdf)

	- Summarizing Slides (Vidal) 
		a nice facilitated content review
[link](http://cis.jhu.edu/~rvidal/talks/learning/Tutorial-Math-Deep-Learning-2018.pdf)


## Image Reconstruction

	- Multi-scale convolutional neural network for pixel-wise reconstruction of Van Gogh’s drawings (Zeng, 2019)
		great work on reconstructing fading drawing (van Gogh) with multi-scale CNN (pixel-wise work)
	
[link](https://link.springer.com/content/pdf/10.1007%2Fs00138-019-01047-3.pdf)

## AI/DL and Physics

	- Deep neural network solution of the electronic Schrödinger equation
[link](https://arxiv.org/pdf/1909.08423v1.pdf?fbclid=IwAR33bpri3oJBIgTjnQIYRC6FvBHpJrbgcqHeUmfKAcnTwcLqXQ1cFW2TApw)

	- Cosmological constraints with deep learning from KiDS-450 weak lensing maps (Fluri et all, 2019)
		trying to prove dark matter/energy via DL
		more divulgatively (not at all) https://ethz.ch/en/news-and-events/eth-news/news/2019/09/artificial-intelligence-probes-dark-matter-in-the-universe.html
[link](https://journals.aps.org/prd/abstract/10.1103/PhysRevD.100.063514)

## Climate Changes

	Tackling Climate Change with Machine Learning (Various authors, including Bengio, Andrew Ng and other bigs, June 2019)

[link](https://arxiv.org/pdf/1906.05433.pdf?fbclid=IwAR0DJnNY8tfZ8VqiegeYWaSbir8c2uzlpUqnK2JyIsIUW5lKLMwAk6tDzhY)	
	
## To give a look

	- Making the Invisible Visible: Action Recognition Through Walls and Occlusions (Li et all, 2019)
[link](https://arxiv.org/abs/1909.09300)
