# Spin 1/2 

## _Concepts used in this articlee:_

* Eigenvectors/values

* Matrix notation/manipulation

## _Introduction_
The most common misconception about spin is to picture an electron rotating around an axis that would pass through its "center of mass". This is incorrect because the electron is a infinitely small particle (radius = 10<sup>-18</sup>m). Therefore, it has been calculated that if the electron was orbiting around its center of mass, it would have a speed which is about a million times the speed of light (The science asylum, 2017). This is why, the spin of an electron has to be seen as an intrinsic property of the electron, such as charge for example. Spin could be more accurately called intrinsic angular momentum (Sakurai & Napolitano, 2017). Thus, the spin of an electron does not depend on its position relative to a coordinate system (Griffith & Schroeter, 2018). This article will focus on spin 1/2, which is the spin that all fermions possess.

## _Stern-Gerlach experiment_

The Stern-Gerlach experiment was performed in 1922 by Otto Stern and Walhter Gerlach. The first experiment conducted with the apparatus allowed the duo to demonstrate that the electron has two spin states: spin up and spin down. They also found the values of those states as being ± ℏ/2(Sakurai & Napolitano, 2017).

The experiment works as follows, silver atoms are heated in an oven which possesses a small hole. Then, a  beam of those silver atoms goes through the hole of the oven and passes through aligned slits. After the slits, the beam passes through an inhomogeneous magnetic field. This one is produced by the poles of a magnet. One pole has a sharp side which is why the magnetic field is inhomogeneous. The silver electron beams passes between the two poles of the magnet. After the magnet a glass plate was positioned in order to determine the position of the silver atoms (Sakurai & Napolitano, 2017; The Editors of Encyclopaedia Britannica, 2009).

Silver atoms were used because they have a free electron (Sakurai & Napolitano, 2017). The spin of the unpaired electron allows the particle to behave as a magnet (The Editors of Encyclopaedia Britannica, 2009). As the orientation of the silver atoms is not defined prior to the experiment, it was expected that the atoms would spread through a continuous line on the glass plate (as would be observed if the electron behaved classically). However, when the experiment was performed, it was observed that only two points were formed on the glass plate. This means that the atoms, after being submitted to an inhomogeneous magnetic field, were divided into two paths. Calculations were performed and it was found that the two paths were meeting the glass plate at +- ℏ/2 (Sakurai & Napolitano, 2017).

## _Spin states_

One of the difficulties that many students face is the differentiation between spin states and laboratory measurements . In fact, there are only two possible spin states, up and down and those lie in a 2D space, called the Hilbert space. On the other hand, when measurements are performed in laboratory conditions, the intrinsic angular spin has three components, one for each direction (Zhu & Singh 2011).
The spin states, spin up and spin down can be represented respectively by:

![](https://latex.codecogs.com/svg.latex?%5Cchi_%2B%20%3D%20%5Cbegin%7Bbmatrix%7D%201%5C%5C%200%5Cend%7Bbmatrix%7D)

![](https://latex.codecogs.com/svg.latex?%5Cchi_-%20%3D%20%5Cbegin%7Bbmatrix%7D%200%5C%5C1%20%5Cend%7Bbmatrix%7D)

If the spin state of a particle with an undefined spin is measured, there is 50% probability that it will be spin up and a 50% probability that it will be spin down (this was demonstrated by the Stern-Gerlach experiment). The eigenvalue for the spin up state is +ℏ/2 and the eigenvalue for the spin down state is -ℏ/2 (Griffith & Schroeter 2018; Susskind & Friedman, 2014). 

If the spin of a particle is measured in one direction, let’s say the z-direction, and the measurements says that the particle is in the spin up state. This means that we are 100% sure that the particle is spinned up in the z-direction. However, it means that we are uncertain about the spin state in the y-direction and x-direction. It is possible to calculate probabilities of getting spin up or spin down for those directions. If a second measurement is performed on the same particle but in the x-direction, then we will know with certainty the orientation of the spin in this direction but we lose knowledge about the spin direction in the z-direction (Griffith & Schroeter 2018). Therefore, the spin operators are incompatible observables. 

The spin operators <sup>1</sup> are:

![](https://latex.codecogs.com/svg.latex?%5Cwidehat%7B%20S_%7Bx%7D%20%7D%20%3D%20%5Cfrac%7B%20%5Chbar%20%7D%7B2%7D%20%5Cbegin%20%7Bpmatrix%7D%200%20%26%201%20%5C%5C%201%20%26%200%5Cend%7Bpmatrix%7D%24%20%24%5Cwidehat%7B%20S_%7Bz%7D%20%7D%20%3D%20%5Cfrac%7B%20%5Chbar%20%7D%7B2%7D%20%5Cbegin%20%7Bpmatrix%7D%201%20%26%200%20%5C%5C%200%20%26%20-1%5Cend%7Bpmatrix%7D%24%20%24%5Cwidehat%7B%20S_%7By%7D%20%7D%20%3D%20%5Cfrac%7B%20%5Chbar%20%7D%7B2%7D%20%5Cbegin%20%7Bpmatrix%7D%200%20%26%20-i%20%5C%5C%20i%20%26%200%5Cend%7Bpmatrix%7D)

You may encounter the in some textbooks the matrices without the coefficient ℏ/2. Those are called the Pauli spin matrices and are represented by σx, σy and σz.

The commutation relationships for the spin operators<sup>2</sup> are:

  [Sx, Sy]=iℏSz     [Sy,Sz]=iℏSx      [Sz,Sx]=iℏSy

If the spin state of a particle is given (+ or - 1/2), it is possible to calculate the probability to find the particle spin up or down in the other two dimensions of space. In order for those calculations to be performed, the following probability equations can be used:

### Table 1:

<table>  <tr>
    <th></th>
    <th>z-direction</th>
    <th>x-direction</th>
    <th>y-direction</th>
  </tr>
  <tr>
    <td>spin up</td>
    <td>|a|²</td>
    <td>1/2 |a + b|²</td>
    <td><img src="https://latex.codecogs.com/svg.latex?%5Cfrac%20%7B1%7D%7B%5Csqrt%7B2%7D%7D%20%5Cbegin%7Bpmatrix%7D%201%5C%5C%20i%20%5Cend%20%7Bpmatrix%7D" alt="y spin up"></td>
  </tr>
  <tr>
      <td>spin down</td>
      <td>|b|²</td>
      <td>1/2 |a - b|²</rd>
      <td><img src="https://latex.codecogs.com/svg.latex?%5Cfrac%20%7B1%7D%7B%5Csqrt%7B2%7D%7D%20%5Cbegin%7Bpmatrix%7D%201%5C%5C%20-i%20%5Cend%20%7Bpmatrix%7D" alt="y spin down"></td>
  </tr>
</table>


To demonstrate the mathematics behind those formula, an example will be displayed using ![](https://latex.codecogs.com/svg.latex?%5Cwidehat%7BS_x%7D):
The first step is to find the eigenvalues of the matrix. In order to do so, the characteristic equation<sup>3</sup> of Sx needs to be set equal to 0. This gives: 

![](https://latex.codecogs.com/svg.latex?%5Cbegin%7Bvmatrix%7D%20-%5Clambda%20%26%20%5Cfrac%7B%5Chbar%7D%20%7B2%7D%20%5C%5C%20%5Cfrac%7B%5Chbar%7D%20%7B2%7D%20%26-%5Clambda%20%5Cend%7Bvmatrix%7D%20%3D%200) The eigenvalues of this equation are ![](https://latex.codecogs.com/svg.latex?%5Cpm%20%5Cfrac%7B%5Chbar%7D%20%7B2%7D)

Then, the components of the eigenvectors can be found using the following formula:![](https://latex.codecogs.com/svg.latex?%5Cwidehat%7B%20S_%7Bx%7D%20%7D%20%20%20%5Cbegin%7Bbmatrix%7D%20%5Calpha%20%20%5C%5C%20%5Cbeta%20%20%5Cend%7Bbmatrix%7D%20%3D%20%5Cpm%20%20%5Cfrac%7B%20%5Chbar%20%7D%7B2%7D%20%5Cbegin%7Bbmatrix%7D%20%5Calpha%20%20%5C%5C%20%5Cbeta%20%5Cend%7Bbmatrix%7D) .Plugging in the operator Sx, we find that ![](https://latex.codecogs.com/svg.latex?%5Calpha%20%3D%20%5Cpm%20%20%5Cbeta). We are looking for probabilities, thus we know that ![](https://latex.codecogs.com/svg.latex?%20%5Cmid%20%20%5Calpha%20%20%20%20%5Cmid%20%5E%7B2%7D%20%2B%20%5Cmid%20%20%5Cbeta%20%20%20%20%20%5Cmid%20%5E%7B2%7D%20%3D1).

When the particle is spin up (eigenvalue +ℏ/2), the eigen spinor will be:![](https://latex.codecogs.com/svg.latex?%5Cchi%20_%7B%2B%7D%3D%20%5Cbegin%7Bbmatrix%7D%20%5Cfrac%7B1%7D%7B%20%5Csqrt%7B2%7D%20%7D%20%20%5C%5C%20%5Cfrac%7B1%7D%7B%20%5Csqrt%7B2%7D%20%7D%20%20%5Cend%7Bbmatrix%7D) .

When the particle is spin down (eigenvalue -ℏ/2), the eigen spinor will be:![](https://latex.codecogs.com/svg.latex?%5Cchi%20_%7B-%7D%3D%20%5Cbegin%7Bbmatrix%7D%20%5Cfrac%7B1%7D%7B%20%5Csqrt%7B2%7D%20%7D%20%20%5C%5C%20%20-%20%20%5Cfrac%7B1%7D%7B%20%5Csqrt%7B2%7D%20%7D%20%20%20%5Cend%7Bbmatrix%7D)  .

Knowing those, we can rewrite the equation as follows, ![](https://latex.codecogs.com/svg.latex?%5Cchi%20%3D%20%20%5Cbig%28%20%5Cfrac%7Ba%2Bb%7D%7B%20%5Csqrt%7B2%7D%20%7D%20%5Cbig%29%5Cchi_%2B%5E%7B%28x%29%7D%20%2B%20%5Cbig%28%20%5Cfrac%7Ba-b%7D%7B%20%5Csqrt%7B2%7D%20%7D%20%5Cbig%29%5Cchi_-%5E%7B%28x%29%7D) , with ‘a’ being the first element of the first row of the matrix and ‘b’ the first element of the second row. For example, if an exercise tells us that a particle with a spin -1/2 is in the following state, ![](https://latex.codecogs.com/svg.latex?%5Cchi%20%3D%20%5Cfrac%7B1%7D%7B%5Csqrt%7B6%7D%20%7D%5Cbegin%20%7Bpmatrix%7D%202-i%5C%5C%201%20%5Cend%7Bpmatrix%7D), ‘a’ would be 2-i and ‘b’ would be 1. The probabilities can be calculated using the formula in Table 1 (Remember: to square a complex number, it needs to be multiplied by its complex conjugate). All the probabilities formula in table 1 can be found using the same methodology (Griffith & Schroeter 2018).

Finally, if the eigenstates of an operator are orthogonal, the eigenstates of different operators are not orthogonal with each other. For example, the eigenstates of ![](https://latex.codecogs.com/svg.latex?%5Cwidehat%7BS_y%7D) which are + or - ℏ/2 are orthogonal but the eigenstates of ![](https://latex.codecogs.com/svg.latex?%5Cwidehat%7BS_y%7D) are not orthogonal with the eigenstates of ![](https://latex.codecogs.com/svg.latex?%5Cwidehat%7BS_x%7D) or ![](https://latex.codecogs.com/svg.latex?%5Cwidehat%7BS_z%7D). This is due to the fact that the eigenstate of an operator span the Hilbert space (2D) in which the spin state is defined while the different components form a 3D space. In addition, the eigenstates of one direction are not orthogonal with a magnetic field that would be directed in  this same direction (Zhu & Singh, 2011). 


<sup>1</sup> The complete mathematical demonstration can be found in “Introduction to Quantum mechanics” Section 4.4 (Griffith, 2018). Derivation with bra-ket notation: see “Quantum mechanic: the theoretical minimum” Lecture 2 (Susskind & Friedman, 2014) .

<sup>2</sup> Analogy with angular momentum. For further insight, see“Introduction to Quantum mechanics” Section 4.4 (Griffith, 2018).

<sup>3</sup> The characteristic equation of a matrix (M) is: M-ƛId. (Id is the identity matrix).

## _Particle in a magnetic field_
When a charged particle is placed in a magnetic field, it has a magnetic dipole moment. The dipole previously mentioned is proportional to the spin of the particle. The interaction between the particle and the magnetic field results in a torque, to which an energy is associated. Thus, when considering a particle in a magnetic field, it is necessary to first find the equation of the Hamiltonian and then use the Schrödinger equation.

The Hamiltonian is proportional to the spin operator in the direction of the magnetic field. Thus, the Hamiltonian can be written as , ![](https://latex.codecogs.com/svg.latex?H%3D-%5Cgamma%20BS) where ![](https://latex.codecogs.com/svg.latex?%5Cgamma) is the gyromagnetic ratio, B the magnetic field and S the spin operator corresponding to the direction of the magnetic field (Griffith & Schroeter, 2018; Susskind & Friedman, 2014). As the Hamiltonian does not depend on time the spin state can be expressed as a sum of the spin up state and spin down state each multiplied by a constant (usually denoted a for spin up and b for spin down). The multiplying constants can be found by using the conditions in table 1 at t=0.
When a and b have been found, the expectation values of the spin components in the three dimensions can be calculated. This can be performed using this formula: ![](https://latex.codecogs.com/svg.latex?%3C%20S%5E%2A%3E%20%3D%20%5Cchi_%7B%28t%29%7D%5E%5Ctop%20S%5E%2A%5Cchi_%7B%28t%29%7D) (S* represents the spin operator of the direction of interest) (Griffith & Schroeter, 2018).

The book _“Quantum mechanics: The theoretical minimum”_ (Susskind & Friedman, 2014) shows how a more general formula can be found using the time-dependent angular momentum equation (derived from the Schrödinger equation). This is done by using the bra-ket notation.

## _Additional resources:_

Spin concept: https://www.youtube.com/watch?v=sB1EPGmpzyg

3D animation to visualize spin: https://www.youtube.com/watch?v=3k5IWlVdMbo

## _References_

Griffith D. J. & Schroeter D. F. (2018). Introduction to quantum mechanics (3rd ed.). Cambridge, UK: Cambridge university press. 

Sakurai, J. J., & Napolitano, J. (2014). Modern quantum mechanics (2nd ed.). Cambridge, UK: Cambridge University press.

Susskind, L. & Friedman, A. (2014). Quantum mechanics: the theoretical minimum. Penguin books.

The Editors of Encyclopaedia Britannica (2009). Stern-Gerlach experiment. Encyclopaedia Britannica inc. Retrieved from https://www.britannica.com/science/Stern-Gerlach-experiment.

The Science Asylum (2017, September 23). _What is quantum spin?_ [Video]. Retrieved from: https://www.youtube.com/watch?v=sB1EPGmpzyg&t=237s.

Zhu, G., & Singh, C. (2011). Improving students’ understanding of quantum mechanics via the Stern–Gerlach experiment. American Journal of Physics, 79(5), 499-507.
