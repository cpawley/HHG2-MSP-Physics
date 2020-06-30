[<- Back to index page](https://cpawley.github.io/HHG2-MSP-Physics/)
# Dirac notation

## Concepts used in this article:

  * Inner product
  * Hilbert space
  * Operators
  
<br>

## What is the Dirac notation?

The Dirac notation, also called bra-ket notation, refers to a simpler and more concise way of writing equations. In fact, the bra-ket notation is used to represent the inner 
product of a vector and its complex conjugate. In Quantum mechanics, that inner product lies in the Hilbert space (N-dimensional space). The Dirac notation is composed of a
“bra” <𝛼\⎹ and a “ket” \⎹𝛽> component. Thus, putting those two parts together, the inner product can be written as, <𝛼\⎹𝛽> (Griffith & Schroeter, 2018; Sakurai & Napolitano, 2014).

The dimensions of the vector depends on the degree of freedom of the parameter studied. For example, the spin vector of fermions is a two dimensional vectors because the spin of those particle can be either +1/2 or -1/2 (Sakurai & Napolitano, 2014). 
  
<br>

## Properties of the bra- and the -ket.

The “ket” represents a vector. On the other hand, the “bra” is a more complex concept, indeed, it is the complex conjugate of the “ket” vector. What this means is that when the bra operates on the ket, a number results. The bra- component and the ket-component each have their vector space, called respectively, the bra space and the ket space. The bra space has to be thought of as a mirror image of the ket space. Thus, for any vector in the ket space, there exists a corresponding -bra in the bra-space (Griffith & Schroeter, 2018; Sakurai & Napolitano, 2014). 
The bra- component can also be considered as an order to integrate. In mathematical writing, this can be expressed by:

![](https://latex.codecogs.com/svg.latex?%3Cf%7C%20%3D%20%20%5Cint%20%7B%20f%5E%7B%2A%7D%20%20%5B...%5Ddx) where the -ket vector has to be written instead of [...] (Griffith & Schroeter, 2018).

The inner product formed by the bra-ket has the following property: <𝛽\|𝛼> = <𝛼\|𝛽>*.

The outer product by the -ket bra- combination is written: \|𝛼><𝛽\|.

The eigenkets represent the states in which an oprator can be (for example, the operator Sx can be in the state spin up or spin down). The physical values of the eigenkets are called eigenstates and those are represented by eigenvalues (Sakurai & Napolitano, 2014). 
  
<br>

## Operations with the Dirac notation

The -ket vector can be multiplied by a scalar and the result would be another ket. If a sum of two -ket vectors (which have the same dimension) is performed then, the result
will be a different -ket. In physics, only the direction of the vector within the vector space is meaningful. Thus, |𝛽> and c|𝛽> represents the same state (Sakurai & Napolitano, 2014). 

Most observables in Quantum Machanics are represented by operators. The operators can act on -kets from the left side and this operation will give another -ket. When 
an operator acts on a -bra it is from the right side and the operation will give another bra -(Sakurai & Napolitano, 2014). 

**Associative axiom of multiplication**: When a -ket is multiplied by an outer product, the outer product act as an operator on the -ket vector. This is demonstarted by: 
(|𝛽><𝛼|)*|μ> = |𝛽>*(<𝛼|μ>). On the right side of the equation, the inner product will give a number, thus the vector 𝛽 will be multiplied by a number. As stated above, a 
-ket multplied by a scalar will give another -ket (Sakurai & Napolitano, 2014). This property of the Dirac notation is used to define an Hemitian operator: <𝛽|X|𝛼> (1) = <𝛼|Xꭞ|𝛽>, where X is |𝛽><𝛼| and Xꭞ is |𝛼><𝛽| (Griffith & Schroeter, 2018; Sakurai & Napolitano, 2014).

**Operator rules**: If a -ket vector is multiplied by the sum of two operators, the equation can be rewritten has the sum of the operator acting on the -ket. In mathematic language, this gives: ![](https://latex.codecogs.com/svg.latex?%28%20%5Cwidehat%7BQ%7D%20%2B%20%5Cwidehat%7BR%7D%29%7C%20%5Calpha%20%3E%20%3D%20%5Cwidehat%7BQ%7D%7C%5Calpha%3E%20%2B%20%5Cwidehat%7BR%7D%7C%5Calpha%3E%20).
If a ket vector is multiplied by several operators, those have to be applied from left to right (Remember: the operators cannot commute with each other). If this is written as a formul, it gives: ![](https://latex.codecogs.com/svg.latex?%5Cwidehat%7BQ%7D%20%20%5Cwidehat%7BR%7D%7C%20%5Calpha%20%3E%20%3D%20%5Cwidehat%7BQ%7D%28%5Cwidehat%7BR%7D%7C%5Calpha%3E%20%29), in this case, the operator R has to be applied first (Griffith & Schroeter, 2018).
  
<br>

## Dirac notation in Quantum mechanics ##

In Quantum mechanics, the expectation values of observables are calculated by integrating wavefunctions. There is an operator corresponding to each observable. For example, the momentum operator is: ![](https://latex.codecogs.com/svg.latex?-i%20%5Chbar%20%20%5Cfrac%7B%5Cpartial%7D%7B%5Cpartial%20x%7D%20). Thus, if one wants to calculate the expectation value of the momentum, it can be done using: ![](https://latex.codecogs.com/svg.latex?%3Cp%3E%20%3D%20%20%5Cint_%7B-%20%5Cinfty%20%7D%5E%20%5Cinfty%20%20%7B%20%5Cpsi%20%20%5E%20%5Cast%20%5B-i%20%5Chbar%20%20%5Cfrac%7B%5Cpartial%7D%7B%5Cpartial%20x%7D%20%5D%20%5Cpsi%20dx). If we look at our equation (1) above about the Hemitian operator, the same structure can be observed. In fact, in the momentum example, the ψ* is the complex conjugate of the wavefunction, ψ. The operator is squeezed between the complex conjugate wavefunction and the wavefunction and thus, it acts on the wavefunction. In this case, the operator tells us that we need to multiply the derivative with regards to x of the wavefunction by -iℏ. 

Expectation value of the momentum: <ψ*|p|ψ>. this equation has the same meaning as the integral above.
  
<br>

## Additional Resources:

Bra-ket with vectors: [https://www.youtube.com/watch?v=xdSTZYc8uRg](https://www.youtube.com/watch?v=xdSTZYc8uRg)

Bra-ket with operators: [https://www.youtube.com/watch?v=2HJSf-kkN1U](https://www.youtube.com/watch?v=2HJSf-kkN1U)

What are “bra” and “kets”:[https://www.youtube.com/watch?v=fIYIFCVICcA](https://www.youtube.com/watch?v=fIYIFCVICcA)

For a complete (advanced) description of Dirac notation see chapter 1, section 1.2 and 1.3 of Sakurai, J. J., & Napolitano, J. (2014). Modern quantum mechanics (2nd ed.). 
Cambridge, UK: Cambridge University press.
  
<br>

## References ##

Griffith D. J. & Schroeter D. F. (2018). Introduction to quantum mechanics (3rd ed.). Cambridge, UK: Cambridge university press.

Sakurai, J. J., & Napolitano, J. (2014). Modern quantum mechanics (2nd ed.). Cambridge, UK: Cambridge University press.
