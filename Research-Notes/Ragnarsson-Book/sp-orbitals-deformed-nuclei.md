# Single-particle orbitals in deformed nuclei

- For spherically deformed nuclei, the isotropic harmonic-oscillator is a field that describes the nuclear spectra in terms of the energy,
- In order to amend for the radial deficiencies, the addition of a term proportional to $-l^2$ has the desired properties:
	- effective interpolation of square well
	- interpolation of h.o.
- As a result, a reproduction of the spherical single-particle levels can be achieved by the usage of the **modified-oscillator (MO) Hamiltonian**:
- $$H_\text{sph}=-\frac{\hbar^2}{2M}\Delta+\frac{1}{2}M\omega_0^2r^2-Cl\cdot s-D\left(l^2-\langle l^2\rangle_n\right)$$
	- There is a general compression of the distance between the shells below $h\omega_0$. 
	- This basic energy spacing is restored by the subtraction of the term $\langle l^2\rangle_N=N(N+3)/2$ -> **constant value within each shell**.
- The eigenfunctions of the spherical shell:
	- ![[Pasted image 20210803064304.png]]

## Single-particle Hamiltonian

- the potential extension along the nuclear $z$-axis (3-axis) being different from the extension along the $x$- and $y$-axes, we may write the single-particle Hamiltonian in the form:
- ![[Pasted image 20210803064941.png]]
- The anisotropy appears due to the difference between $\omega_\perp$ and $\omega_z$
- Elongation parameter introduced by Nilsson $\epsilon$:
- ![[Pasted image 20210803065142.png]]




## Modified oscillator (MO) potential

![[Pasted image 20210803070225.png]]

- the last term in the parentheses has the effect of interpolating between the oscillator and the square well -> reproduces the Woods-Saxon radial shape
- The $l^2$ term alone would result in a general compression of the shells
- This is avoided by subtracting the average value of $\langle l^2 \rangle$
- ![[Pasted image 20210803070530.png]]

For the atomic case (the electron case), the total wave-function is written as a product of wave function: ![[Pasted image 20210803085737.png]]
where the one-electron wave-functions are given by $\phi_i$.

- the potential seen by electron $i$ under the influence of the nucleus and the remaining $Z-1$ electrons placed statically in the nucleus:
- ![[Pasted image 20210803085849.png]], which leads to the one-particle Schrodinger equation: ![[Pasted image 20210803085918.png]] with the energy eigenvalues $e_i$.

In the nuclear case, there is no central potential -> the two-particle interaction is not fully determined

- A feasible approach is to use the **mean-field potential**: ![[Pasted image 20210803090154.png]] where the two-particle interactions $V_{ij}$ in the general case not only depend on distance but also on angular momentum and spin

## Perturbation treatment for small $\epsilon$

Study of the Hamiltonian for small $\epsilon$-values.

$$H=H_0+\epsilon h'+\mathcal{O}(\epsilon^2)+\dots$$

where $H_0$ is the spherical shell model Hamiltonian