# Problem Set 1: Vectors, Dot Products, and Geometric Intuition

## Warm-up

**Problem 1.** Let **u** = (3, 4) and **v** = (−1, 2). Compute:
- (a) **u** + **v**
- (b) 2**u** − **v**
- (c) ‖**u**‖ and ‖**v**‖

**Problem 2.** Find a unit vector in the direction of (5, −12).

## Dot Products

**Problem 3.** Compute the dot product **u** · **v** for **u** = (1, 2, 3) and **v** = (4, −5, 6). Is the angle between them acute, right, or obtuse?

**Problem 4.** Prove that for any vector **v** in ℝⁿ, **v** · **v** = ‖**v**‖².

**Problem 5.** Let **u** = (1, 1) and **v** = (3, 0). Find the scalar projection of **u** onto **v**, and the vector projection of **u** onto **v**. Sketch it.

## Geometric Intuition

**Problem 6.** Two vectors in ℝ² have lengths 5 and 8, and their dot product is −20. What is the angle between them?

**Problem 7.** Show that **u** and **v** are orthogonal if and only if ‖**u** + **v**‖² = ‖**u**‖² + ‖**v**‖². (This is the Pythagorean theorem in disguise — expand and simplify.)

**Problem 8.** Let **v** = (2, 1, −1) and **w** = (1, −1, 1). Find a vector **p** that is the projection of **v** onto **w**, and a vector **e** = **v** − **p** that is orthogonal to **w**. Verify that **e** · **w** = 0.

## Thinking Toward ML

**Problem 9.** Cosine similarity between two vectors is defined as:

cos_sim(**u**, **v**) = (**u** · **v**) / (‖**u**‖ ‖**v**‖)

- (a) Compute the cosine similarity of (1, 0, 1) and (0, 1, 1).
- (b) What is the range of cosine similarity? When does it equal 1? When −1? When 0?
- (c) Why might cosine similarity be preferred over dot product for comparing word embeddings of different magnitudes?

**Problem 10.** A simple linear classifier predicts "positive" if **w** · **x** + b > 0 for weight vector **w** and input **x**. Let **w** = (2, −1) and b = −3.
- (a) Classify the points (3, 1) and (1, 0).
- (b) What is the geometric meaning of the set {**x** : **w** · **x** + b = 0}? Sketch it.
- (c) Which direction does **w** point relative to this decision boundary?

## Derivations

**Q1: Law of Cosines.** Given a triangle with sides a, b, c and angle θ between a and b, place it in coordinates and derive:

c² = a² + b² − 2ab cos(θ)

*Hint:* Put one side on the x-axis, express the third point using (b cos θ, b sin θ), apply distance formula.

**Q2: Dot Product Identity.** For **u**, **v** ∈ ℝⁿ, show:

**u** · **v** = ‖**u**‖ ‖**v**‖ cos(θ)

*Hint:* Expand ‖**u** − **v**‖² algebraically and via law of cosines, then equate.
