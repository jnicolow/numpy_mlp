Implementing a simple neural network in numpy

### Forward Pass



\[
x \in \mathbb{R}^D
\]





\[
z = W x + b_1 \in \mathbb{R}^K
\]





\[
h = \mathrm{ReLU}(z) \in \mathbb{R}^K
\]





\[
a = U h + b_2 \in \mathbb{R}^C
\]





\[
L = \mathrm{CrossEntropy}\big(y,\ \mathrm{softmax}(a)\big) \in \mathbb{R}
\]


