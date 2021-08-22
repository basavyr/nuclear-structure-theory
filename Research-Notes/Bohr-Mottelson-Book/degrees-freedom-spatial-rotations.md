# Degrees of freedom associated with spatial rotations

- Rotational motion about a fixed axis -> **rotational motion in two dimensions**
- The 2D rotation implies only two parameters that are used to describe this kind of motion: `a)` the azimuthal angle $\phi$ -> **orientation of the system** and `b)` the state of the motion given by the eigenvalue $M$ of the total angular momentum. Per the two parameters, the expression of the associated wave function is as follows: ![[Pasted image 20210821145532.png]]
- Taking the rotational motion in 3D, the orientation of the nuclear body involves three parameters: **the Euler angles**
- Moreover, for the 3D rotation of the nuclear system, three quantum numbers are required for the state of motion. These three quantum numbers are :
	- the total angular momentum $I$
	- the $M$ component on the *space-fixed axis*-$I_z$ (space-fixed coordinate system)
	- the $K$ component of the *body-fixed axis*-$I_3$ (body-fixed coordinate system)
		- The third quantum number can be obtained by considering the components of $\vec{I}$ w.r.t. to *the intrinsic* (or body-fixed) coordinate system with given **orientation** $\omega$. The orientation is also defined in Bohr's NS-I book within the following subsection ![[Pasted image 20210822120340.png]]
		- The diagram shown below aims at depicting the difference between the intrinsic coordinate system and the space-fixed (or the *laboratory*) system. 
  
  ![](nuclear-body-orientation.png)
  
  - If the three quantum numbers that define the state of motion for the nuclear body are known/defined, then the rotational wave function is given by the expression: $$\varphi_{IKM}(\omega)=\left(\frac{2I+1}{8\pi^2}\right)^{1/2}\mathcal{D}^I_{MK}(\omega)$$
  - The above formula can be obtained by applying a transformation from the **fixed coordinate system** to a **rotated coordinate system** which coincides with the intrinsic frame. This kind of transformation is described in Bohr's NS-I book #bohrNS1.
	  - ![[Pasted image 20210822121608.png]]
	  - ![[Pasted image 20210822123150.png]]

## Wave functions describing orientation of intrinsic system

- This sub-section is devoted to the explanation of the workflow involved in obtaining the formula ![[Pasted image 20210822123513.png]]
- The **state of orientation** of the body-fixed system is completely specified by the three angular momentum quantum numbers $IKM$
	- These three numbers represent the conjugates of the three orientation angles $\omega=(\phi,\theta,\psi)$.
	- The transformation [[1A-34]] is required in order to pass from the basis set $|\omega\rangle$ with a *sharply defined orientation* to the basis set $|IKM\rangle$. This is applied to a coordinate system $H'$ with orientation $\omega$ w.r.t. to $H$ ![[Pasted image 20210822124036.png]]
	- The state $|\omega\rangle$ with orientation $\omega$ w.r.t to $H$ has the orientation $\omega_0=0$ w.r.t to $H'$. ![[Pasted image 20210822124721.png]]
	- Using these two statements from above, the following relation holds:
		- ![[Pasted image 20210822125017.png]] #rotational-wave-function
	- The scalar product between the **zero-orientation** and a rotated state $|IKM'\rangle$ will vanish, unless $M'=K$.
		- This happens because both components of the total angular momentum $I_3$ and $I_z$ are equal when acting on the state $|\omega_0=0\rangle$. This arises from ![[Pasted image 20210822130957.png]]
	- The rotational wave-function described above #normalized-wave-function can be written in a *normalized* form, using the equation [[1A-41]] via the choice of phase: $$\Phi_{IKM}(\omega)=\left(\frac{2I+1}{8\pi^2}\right)^{1/2}\mathcal{D}^I_{MK}(\omega)$$

## Wigner-D physical significance

- The $\mathcal{D}$ functions can be viewed as the wave functions describing the **orientation** of a dynamical system with:
	- specified angular momentum quantum numbers
- In the case of a **single particle (spin-zero) in a potential** (or the relative motion of two particles without spin), the intrinsic angular momentum $K$ is constrained to have the value zero
	- the orientation wave-function reduce to the more familiar spherical harmonics
- While $\vec{I}^2$ and $I_z$ are constants of the motion for any system with rotational invariance:
	- the commutator of the Hamiltonian $H$ with $I_3$ depends on the intrinsic dynamics of the system
	- the stationary states do not possess a definite $K$ value


## Transformation laws for the rotational wave function as described by the three quantum numbers $IKM$
![[Pasted image 20210822133547.png]]

- For null $K$, the Wigner functions reduce to the well-known spherical harmonics ![[Pasted image 20210822133649.png]]
- For $K=0$ the rotational wave function is the same as for the angular motion of a **point particle with no spin**.
- For $K$ finite, the rotational motion corresponds to the angular motion of a particle with helicity $h=K$.

