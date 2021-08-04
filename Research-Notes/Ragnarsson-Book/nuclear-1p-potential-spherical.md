# The nuclear one-particle potential in the spherical case

The task at hand is to find the solution/wave-function of the following Hamiltonian:

$$ H=-\frac{\hbar^2}{2M}\Delta^2+V(r)$$
where $V(r)$ is to represent the *nuclear one-body* potential (the one-body field), and $M$ is the average nucleon mass. Using the spherical symmetry and working in the spherical coordinates, one can exploit the symmetries involved in order to postulate a potential candidate to the solution; namely the function $\psi=R(r)Y_{lm}(\theta,\varphi)$, where $Y_{lm}$ is an eigenfunction of the angular momentum operator $l^2$. ![[Pasted image 20210804092358.png]]

The Schrodinger equation for the radial wave function $R(r)$ is given by the following expression: ![[Pasted image 20210804092534.png]]

- A common type of radial potential is the Woods-Saxon potential: ![[Pasted image 20210804092608.png]]. However, the Schrodinger can only be **solved numerically** for this kind of potential.
- The WS potential falls somewhere between the **harmonic oscillator** and the **finite square well** potentials

### Harmonic oscillator potential

- there is a degeneracy in addition to that caused by the spherical symmetry
- By a *remarkable coincidence*, the second root $2s$ for $l=0$ of the potential exactly coincides with the first root $1d$ of the $l=2$ potential
- This coincidence is understood in terms of the $SU_3$ group. See more details about the $SU_3$ group [here](../../Research-Materials/su3.pdf).

### Infinite square-well potential

- The $l$-degeneracy of the oscillator shells is split such that the $1d$ falls below $2s$, $1g$ below $2d$, the latter in turn below $3s$
- The splitting can be understood if one considers the effective radial potential where the **centrifugal potential** has been added to $V(r)$: $$V_\text{eff}=V(r)+\frac{\hbar^2}{2Mr^2}l(l+1)$$
- The potential above enters in the separated radial equation
- The level ordering in the Woods-Saxon case falls somewhere between the two extremes, the soft-surface harmonic oscillator, and the hard-surface square well. The same level ordering is obtained y the addition of a term $$V_\text{corr}=-\mu'\hbar\omega_0l(l+1)$$ to the harmonic oscillator potential.
- ![[Pasted image 20210804123001.png]] ![[Pasted image 20210804123014.png]] ![[Pasted image 20210804123042.png]]

## Spin-orbit term

- One required task is to reproduce the energy gap for 50 protons or neutrons.
- This can be achieved if the 1g-shell splits into $g_{9/2$} and $g_{7/2}$
- In a similar way, the splitting of the 1h-shell into $h_{11/2}$ and $h_{9/2}$ leads to a gap for a particle number of 82, and so on.