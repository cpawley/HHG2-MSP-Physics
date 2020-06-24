# Spin 1/2 

## _Concepts required to understand this article:_

* Knowing how to calculate Eigenvector/values

* Matrix notation/manipulation

* How the angular momentum is derived from the Schrödinger equation

## _Introduction_
The most common misconception about spin is to picture an electron rotating around an axis that would pass through its center of mass. This is incorrect because the electron is a infinitely small particle (radius = 10<sup>-18</sup>m). Therefore, it has been calculated that if the electron was orbiting around its center of mass, it would have a speed which is about a million times the speed of light (The science asylum, 2017). This is why, the spin of an electron has to be seen as an intrinsic property of the electron, such as charge for example. Spin could be more accurately called intrinsic angular momentum (Sakurai & Napolitano, 2017). This means that the spin of an electron does not depend on its position relative to a coordinate system (Griffith & Schroeter, 2018). This article will focus on spin 1/2, which is the spin that all fermions possess.

## _Stern-Gerlach experiments_

The Stern-Gerlach experiment was performed in 1922 by Otto Stern and Walhter Gerlach. The first experiment conducted with the apparatus allowed the duo to demonstrate that the electron has two spin states: spin up and spin down. They also found the values of those states as being ± ℏ/2(Sakurai & Napolitano, 2017).

The experiment works as follows, silver atoms are heated in an oven which possesses a small hole. Then, a  beam of those silver atoms go through the hole of the oven before passing through aligned slits. After the slits, the beam passes through an inhomogeneous magnetic field. This one is produced by the poles of a magnet. One pole has a sharp side which is why the magnetic field is inhomogeneous. After the magnet a glass plate was positioned in order to determine the position of the silver atoms (Sakurai & Napolitano, 2017; The Editors of Encyclopaedia Britannica, 2009).

Silver atoms were used because they have a free electron (Sakurai & Napolitano, 2017). The spin of the unpaired electron allows the particle to behave as a magnet. Therefore, it has a north and south pole (The Editors of Encyclopaedia Britannica, 2009). 

As the orientation of the silver atoms is not defined, it was expected that the atoms would spread through a continuous line on the glass plate. However, when the experiment was performed, it was observed that only two points were formed on the glass plate. This means that the atoms, after being submitted to an inhomogeneous magnetic field, were divided into two paths. Calculations were performed and it was found that the two paths were meeting the glass plate at +- ℏ/2 (Sakurai & Napolitano, 2017).

## _Spin states_

One of the difficulties that many students face is the differentiation between spin states and laboratory measurements . In fact, there are only two possible spin states, up and down and those lie in a 2D space, called the Hilbert space. On the other hand, when measurements are performed in laboratory conditions, the intrinsic angular spin has three components, one for each direction (Zhu & Singh 2011).
The spin state is represented by the following, Figure  1 (spin up) and Figure (spin down) *. 

### Figure 1:

![Test](spinup.png)

Figure 2:
![]()

If the spin state of a particle with an undefined spin is measured, there is 50% probability that it will be spin up and a 50% probability that it will be spin down (this was demonstrated by the Stern-Gerlach experiment). The eigenvalue for * C * is ℏ/2 and the eigenvalue for * C * is -ℏ/2 (Griffith & Schroeter 2018; Susskind & Friedman, 2014). 

If the spin of a particle is measured in one direction, let’s say the z-direction, and the measurements says that the particle is in the spin up state. This means that we are 100% sure that the particle is spinned up in the z-direction. However, it means that we are uncertain about the spin in y-direction or x-direction. It is possible to calculate probabilities of getting spin up or spin down for those directions. If a second measurement is performed on the same particle but in the x-direction, then we will know with certainty the orientation of the spin in this direction but we lose knowledge about the spin direction in the z-direction (Griffith & Schroeter 2018). Therefore, the spin matrices, σx, σy and σz (often referred to as Pauli spin matrices) are incompatible observables. The Pauli matrices are denoted by the spin operators without the coefficient ℏ/2 in front. 

The spin operators <sup>1</sup> are:



These matrices follow the commutation relationships for the spin operators<sup>2</sup>:

  [Sx, Sy]=iℏSz     [Sy,Sz]=iℏSx      [Sz,Sx]=iℏSy

If the spin state of a particle is given (+ or - 1/2), it is possible to calculate the probability to find the particle spin up or down in the other two dimensions of space. In order for those calculations to be performed, the following probabilities equation can be used:

### Table 1:

![](Probability_table.png)

To demonstrate the mathematics behind those formula, an example will be displayed using Sx:
The first step is to find the eigenvalues of the matrix. In order to do so, the characteristic equation<sup>3</sup> of Sx needs to be set equal to 0. This gives:
 
The eigenvalues of this equation are +- ℏ/2.

Then, the components of the eigenvectors need to be found using the following general formula: * equation *. Plugging in the operator Sx, we find that * equation *. We are looking for probabilities, thus we know that * equation *. Therefore, * equation *.
When the particle is spin up (eigenvalue +ℏ/2), the eigen spinor will be: * spinor *.
When the particle is spin down (eigenvalue -ℏ/2), the eigen spinor will be: * spinor *.
Knowing those, we can rewrite the equation as follows,  * equation *, with ‘a’ being the first element of the first row of the matrix and ‘b’ the first element of the second row. For example, if an exercise tells us that a particle with a spin -1/2 is in the following state, * state * , ‘a’ would be 2-i and ‘b’ would be 1. The probabilities can be calculated using the formula in Table 1 (Remember: to square a complex number, it needs to be multiplied by its complex conjugate). All the probabilities formula in table 1 can be found using the same methodology (Griffith & Schroeter 2018).

Finally, if the eigenstates of an operator are orthogonal, the eigenstates of different operators are not orthogonal with each other. For example, the eigenstates of Sy which are + or - ℏ/2are orthogonal but the eigenstates of Sy are not orthogonal with the eigenstates of Sx or Sz. This is due to the fact that the eigenstate of an operator span the Hilbert space (2D) in which the spin state is defined while the different components form a 3D space. In addition, the eigenstates of one direction are not orthogonal with a magnetic field that would be directed in  this same direction (Zhu & Singh, 2011). 


<sup>1</sup> The complete mathematical demonstration can be found in “Introduction to Quantum mechanics” Section 4.4 (Griffith, 2018). Derivation with bra-ket notation: see “Quantum mechanic: the theoretical minimum” Lecture 2 (Susskind & Friedman, 2014) .

<sup>2</sup> Analogy with angular momentum. For further insight, see“Introduction to Quantum mechanics” Section 4.4 (Griffith, 2018).

<sup>3</sup> The characteristic equation of a matrix (M) is: M-ƛId. (Id is the identity matrix).

## _Particle in a magnetic field_
When a charged particle is place in a magnetic field, it has a magnetic dipole moment. The dipole previously mentioned is proportional to the spin of the particle. The interaction between the particle and the magnetic field results in a torque, to which an energy is associated. Thus, when considering a particle in a magnetic field, it is necessary to first find the equation of the Hamiltonian and then use the Schrödinger equation.

The Hamiltonian is proportional to the spin operator in the direction of the magnetic field. Thus, the Hamiltonian can be written as img img src"https://render.githubusercontent.com/render/math?math=\(H=-\gammaBS\)", where \gamma is the gyromagnetic ratio, B the magnetic field and S the spin operator corresponding to the direction of the magnetic field (Griffith & Schroeter, 2018; Susskind & Friedman, 2014). As the Hamiltonian does not depend on time the spin state can be expressed as a sum of the spin up state and spin down state each multiplied by a constant (usually denoted a for spin up and b for spin down). The multiplying constants can be found by using the conditions in table 1 at t=0.
When a and b have been found, the expectation values of the spin components in the three dimensions can be calculated. This can be performed using this formula: < S*> = (t)S*(t)(Griffith & Schroeter, 2018).

The book “Quantum mechanics: The theoretical minimum”(Susskind & Friedman, 2014) shows how general formula can be found using the time-dependent angular momentum equation (derived from the Schrödinger equation). This is done by using the bra-ket notation.

## _Additional resources:_

Spin concept: https://www.youtube.com/watch?v=sB1EPGmpzyg

3D animation to visualize spin: https://www.youtube.com/watch?v=3k5IWlVdMbo

## _References_

Griffith D. J. & Schroeter D. F. (2018). Introduction to quantum mechanics (3rd ed.). Cambridge, UK: Cambridge university press. 

Sakurai, J. J., & Napolitano, J. (2014). Modern quantum mechanics (2nd ed.). Cambridge, UK: Cambridge University press.

Susskind, L. & Friedman, A. (2014). Quantum mechanics: the theoretical minimum. Penguin books.

The Editors of Encyclopaedia Britannica (2009). Stern-Gerlach experiment. Encyclopaedia Britannica inc. Retrieved from https://www.britannica.com/science/Stern-Gerlach-experiment.

Zhu, G., & Singh, C. (2011). Improving students’ understanding of quantum mechanics via the Stern–Gerlach experiment. American Journal of Physics, 79(5), 499-507.

