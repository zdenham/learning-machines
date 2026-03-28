# Course Outline: Math for Machine Learning

A progression from foundational math to the core theory behind deep learning and LLMs.

---

## Phase 1: Foundations

Core math tools used everywhere in ML.

### Linear Algebra
1. Vectors, dot products, and geometric intuition
2. Matrices as linear transformations
3. Matrix multiplication and composition of transformations
4. Determinants and invertibility
5. Eigenvalues and eigenvectors
6. Singular Value Decomposition (SVD)
7. Principal Component Analysis (PCA) as an application

### Calculus
8. Limits, derivatives, and the chain rule
9. Partial derivatives and gradients
10. Multivariable chain rule
11. Taylor series and local approximations
12. Integrals as accumulation (for probability later)

### Probability & Statistics
13. Probability axioms, conditional probability, Bayes' theorem
14. Random variables, expectation, variance
15. Common distributions (Bernoulli, Gaussian, categorical)
16. Joint distributions and independence
17. Maximum likelihood estimation (MLE)
18. Information theory: entropy, cross-entropy, KL divergence

---

## Phase 2: Optimization

How machines actually learn.

19. Gradient descent — intuition and convergence
20. Stochastic gradient descent and mini-batches
21. Convexity, local minima, saddle points
22. Learning rate schedules and momentum
23. Adam and adaptive methods
24. Lagrange multipliers and constrained optimization

---

## Phase 3: Neural Network Fundamentals

Connecting the math to architectures.

25. The perceptron and linear classifiers
26. Activation functions and why nonlinearity matters
27. Universal approximation theorem (intuition + sketch of proof)
28. Backpropagation — deriving it from the chain rule
29. Computational graphs and automatic differentiation
30. Loss functions: MSE, cross-entropy, and their gradients
31. Regularization: L1, L2, dropout (mathematical framing)
32. Batch normalization — why it helps (and the math behind it)

---

## Phase 4: Sequences and Attention

The path to transformers.

33. Recurrent neural networks and the vanishing gradient problem
34. LSTMs and gating mechanisms
35. Sequence-to-sequence models and the bottleneck problem
36. Attention as weighted averaging
37. Scaled dot-product attention — derivation and intuition
38. Multi-head attention
39. Positional encoding — why and how
40. The full transformer architecture (encoder-decoder walkthrough)

---

## Phase 5: Language Models and Modern AI

Theory behind LLMs.

41. Language modeling as next-token prediction
42. Softmax temperature and sampling strategies
43. Tokenization and embeddings (mathematical view)
44. Training dynamics: loss curves, scaling laws
45. Fine-tuning and transfer learning
46. RLHF — reward modeling and policy optimization
47. Emergent abilities and in-context learning (open questions)

---

## Phase 6: Advanced Topics

Deeper dives for continued study.

48. Convolutions and CNNs (mathematical formulation)
49. Generative models: VAEs and the reparameterization trick
50. Diffusion models — the math of denoising
51. Graph neural networks and message passing
52. Mechanistic interpretability — what's inside the network?

---

*Each topic is roughly one day. Some may take longer — that's fine. Depth over speed.*
