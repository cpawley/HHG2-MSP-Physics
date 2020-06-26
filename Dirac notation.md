# Dirac notation

## Concepts used in this article:

  * Inner product
  * Hilbert space
  * Operators
 
## What is the Dirac notation?

The Dirac notation, also called bra-ket notation, refers to a simpler and more concise way of writing equations. In fact, the bra-ket notation is used to represent the inner 
product of a vector and its complex conjugate. In Quantum mechanics, that inner product lies in the Hilbert space (N-dimensional space). The Dirac notation is composed of a
“bra” <𝛼⎹ and a “ket” ⎹𝛽> component. Thus, putting those two parts together, the inner product can be written as, <𝛼⎹𝛽>.

The dimensions of the vector depends on the degree of freedom of the parameter studied. For example, the spin vector of fermions is a two dimensional vectors because the spin of
those particle can be either +1/2 or -1/2. 

## Properties of the bra- and the -ket.

The “ket” represents a vector. On the other hand, the “bra” is a more complex concept, indeed, it is a complex conjugate of the “ket” vector. What this means is that when the bra 
operates on the ket, a number results. The bra- component and the ket-component each have their vector space, called respectively, the bra space and the ket space. The bra space
has to be thought of as a mirror image of the ket space. Thus, for any vector in the ket space, there exists a corresponding -bra in the bra-space.

The inner product formed by the bra-ket has the following property: <𝛽|𝛼> = <𝛼|𝛽>*.

The outer product by the -ket bra- combination is written: |𝛼><𝛽|.

The eigenkets represent the states in which an oprator can be (for example, the operator Sx can be in the state spin up or spin down). The physical values of the eigenkets are 
called eigenstates and those are represented by eigenvalues. 

## Operations with the Dirac notation

The -ket vector can be multiplied by a scalar and the result would be another ket. If a sum of two -ket vectors (which have the same dimension) is performed then, the result
will be a different -ket. In physics, only the direction of the vector within the vector space is meaningful. Thus, |𝛽> and c|𝛽> represents the same state.

Most observables in Quantum Machanics are represented by operators. The operators can act on -kets from the left side and this operation will give another -ket. When 
an operator acts on a -bra it is from the right side and the operation will give another bra-.

**Associative axiom of multiplication**: When a -ket is multiplied by a outer product, the outer product act as an operator on the -ket vector. This is demonstarted by: 
(|𝛽><𝛼|)*|μ> = |𝛽>*(<𝛼|μ>). On the right side of the equation, the inner product will give a number, thus the vector 𝛽 will be multiplied by a number. As stated above, a 
-ket multplied by a scalar will give another -ket. This property of the Dirac notation is used to define an Hemitian operator: <𝛽|X|𝛼> = <𝛼|Xꭞ|𝛽>, where X is |𝛽><𝛼| and Xꭞ is 
|𝛼><𝛽|.

## Additional Resources:

Bra-ket with vectors: https://www.youtube.com/watch?v=xdSTZYc8uRg

Bra-ket with operators: https://www.youtube.com/watch?v=2HJSf-kkN1U

What are “bra” and “kets”:https://www.youtube.com/watch?v=fIYIFCVICcA

For a complete (advanced) description of Dirac notation see chapter 1, section 1.2 and 1.3 of Sakurai, J. J., & Napolitano, J. (2014). Modern quantum mechanics (2nd ed.). 
Cambridge, UK: Cambridge University press.
