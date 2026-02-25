# Computing-Darmon-Dasgupta-units

This project contains the code used to run the examples of the article "Generating series techniques for computing Darmon-Dasgupta units over real quadratic fields". The computations are done using Sagemath 9.5.

# Usage

Copy the files ending in .ipynb in a Jupyter notebook and run Main.ipynb. You will have to choose a discriminant $D$, a prime $p$ inert in $F=\mathbb{Q}(\sqrt{D})$ and a prime $\ell\geq 5$ different from $p$. 
To each class in the narrow class group of $F$, will be attached a $p$ unit, they are all conjugate to each other, we compute each of them to recognize their minimal polynomial over $F$.

We ran examples for primes $p$ up to $600$, in these cases, a low $p$-adic precision $M$ (for example $M=10$) is enough. 



Note that the computations of our code should match the one of Fleischer-Liu (available here https://github.com/liuyj8526/Computation-of-Elliptic-Units/blob/master/README.md). We use some of their functions (for example getgam in Misc, the file "basis_cocycle" also comes from their github ).


If you have any questions or require help, feel free to contact me at crabit[at]imj-prg.fr.
