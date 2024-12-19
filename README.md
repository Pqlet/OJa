# OJa

# Goal of thr project

## Project statement
Dense representations of the modern DL models are hardly interpretable. In particular, one neuron does not correspond to some sense/pattern/“feature” in the latent representation. 

Moreover, “superposition hypothesis” can explain impossibility to do that.

## Oja's rule

$\Delta w = \eta y (x - y w)$, where $y = x^Tw$

## Sanger's rule
$\Delta w_{ij} = \eta y_i(x_j - \sum_{k=1}^i w_{kj}y_k)$, where $y = x^Tw$

## Modern Hebbian learning
$\Delta w_{ik}^{(SoftHebb)} = \eta y_k(x_i - u_k w_{ik})$, where $y = Softmax(u_k)$, $u_k = xw_k$