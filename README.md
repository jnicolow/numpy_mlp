Implementing a simple neural network in numpy


## Forward Pass

The model computes the following sequence of transformations:



\[
x \in \mathbb{R}^D
\]





\[
z = W x + b_1 \quad\in \mathbb{R}^K
\]





\[
h = \mathrm{ReLU}(z) \quad\in \mathbb{R}^K
\]





\[
a = U h + b_2 \quad\in \mathbb{R}^C
\]





\[
L = \mathrm{CrossEntropy}\big(y,\ \mathrm{softmax}(a)\big) \in \mathbb{R}
\]


