# The nuclear one-particle potential in the spherical case

The task at hand is to find the solution/wave-function of the following Hamiltonian:

$$ H=-\frac{\hbar^2}{2M}\Delta^2+V(r)$$
where $V(r)$ is to represent the *nuclear one-body* potential (the one-body field), and $M$ is the average nucleon mass. Using the spherical symmetry and working in the spherical coordinates, one can exploit the symmetries involved in order to postulate a potential candidate to the solution; namely the function $\psi=R(r)Y_{lm}(\theta,\varphi)$, where $Y_{lm}$ is an eigenfunction of the angular momentum operator $l^2$. ![[Pasted image 20210804092358.png]]

The Schrodinger equation for the radial wave function $R(r)$ is given by the following expression: ![[Pasted image 20210804092534.png]]

- A common type of radial potential is the Woods-Saxon potential: ![[Pasted image 20210804092608.png]]. However, the Schrodinger can only be **solved numerically** for this kind of potential.
- The WS potential falls somewhere between the **harmonic oscillator** and the **finite square well** potentials