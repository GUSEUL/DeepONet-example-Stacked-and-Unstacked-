# DeepONet Examples
One of the simplest example is the following 1D system,

$\frac{ds(x)}{dx} = g(s(x), u(x), x), x \in [0,1]$

with initial condition $s(0) = 0$. The goal is to predict $s(x)$ in [0, 1] for a given $u(x)$.

Using $g(s(x), u(x), x) = u(x)$, we get the following result:

$\frac{ds(x)}{dx} = u(x), x \in [0,1]$

which is the antiderivative operator:

$\mathcal{G} : u(x) \mapsto s(x) = \int_0^x u(t) dt $


## Required Libraries and Versions
-python 3.12.4

-torch 2.3.1+cu118

-gstools 1.6.1

-scipy 1.14.0

-numpy 1.26.4

-matplotlib 3.9.1




