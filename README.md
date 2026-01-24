# Computing-Darmon-Dasgupta-units

This project contains the code used to run the examples of the article "Generating series techniques for computing Darmon-Dasgupta units over real quadratic fields". The computations are done using Sagemath 9.5.

# Usage

Copy the files ending in .ipynb in a Jupyter notebook and run Main.ipynb. You will have to choose a discriminant $D$, a prime $p$ inert in $F=\mathbb{Q}(\sqrt{D})$ and a prime $\ell\geq 5$ different from $p$. 
To each class in the narrow class group of $F$, will be attached two integers $c\geq0,d$ (computed by the function getgam). Make sure that $c$ is not too large before you run the computations.

We ran examples for primes $p$ up to $600$, in this case, a low $p$-adic precision $M$ (for example $M=10$) is enough. 



Note that the computations of our code should match the one of Fleischer-Liu (available here https://github.com/liuyj8526/Computation-of-Elliptic-Units/blob/master/README.md). In Misc.ipynb we use some of their functions (for example getgam).


If you have any questions or require help, feel free to contact me at crabit[at]imj-prg.fr.
