The two most important vector operations are the dot- and cross product. Both of these are based on matrix operations, and while the dot product is easy to do in vector notation, the cross product might be easier to do in matrix notation. 

# Dot Product

The dot product is similar to multiplying vectors, creating a scalar number. When the vectors are not split up into their components, the result of the dot product is 

![alt text](https://github.com/cpawley/HHG2-MSP-Physics/blob/Floris-Images/1%20(2).png),

where θ is the angle between the two vectors. When the components of the vectors are known, meaning there is an equation like Ax + By + Cz, the dot product is performed like this 

![alt text](https://github.com/cpawley/HHG2-MSP-Physics/blob/Floris-Images/2.png)

As shown, the like parts are multiplied together, and the products are added together. The dot product is both cumulative and distributive, meaning the order of the vectors does not matter, and A ・ (B + C) is the same as A・B + A・C.
Due to the angle in the operation, the dot product is the product of the two vectors if they are parallel, and 0 if they are perpendicular. 

# Cross Product

The cross product is completely different from the dot product, especially when it comes to performing it with the components. In normal vector form, the cross product equals 

![alt text](https://github.com/cpawley/HHG2-MSP-Physics/blob/Floris-Images/3.png)

The n with the hat in this equation is a unit vector in the direction perpendicular to the plane of A and B. This means that if A is in the x direction, and B in the y, the cross product will be a new vector in the z direction. When the vectors’ components are known, the cross product is performed by 

![alt text](https://github.com/cpawley/HHG2-MSP-Physics/blob/Floris-Images/4.png)

Due to the disordered nature of this formula, the cross product often can be referred from a 3x3 matrix, like this one. 

![alt text](https://github.com/cpawley/HHG2-MSP-Physics/blob/Floris-Images/5%20(2).png)

The cross product for the x component can then be calculated by taking the determinant of the 2x2 matrix created by the y and z components. This is done by multiplying the cross terms (Ay and Bz, and Az and By), and subtracting the second term from the first, as seen in the original formula for the cross product with components. 
Although the cross product is distributive, the order of the vectors does matter, meaning it is not associative. 
Like in the dot product, the cross product is 0 or AB depending on the angle. However, since there is a sin in front of the angle, the cross product is 0 when the vectors are parallel, and equal to AB when they are perpendicular.

For some extra explanations, mostly on properties, and practice, you can visit:

https://tutorial.math.lamar.edu/Classes/CalcII/CrossProduct.aspx 

https://tutorial.math.lamar.edu/Classes/CalcII/DotProduct.aspx 

For helpful videos, you can scroll through these videos from Khan Academy

https://www.khanacademy.org/math/linear-algebra/vectors-and-spaces/dot-cross-products/v/vector-dot-product-and-vector-length 

Formulas from Griffiths, D. J. (2005). Introduction to electrodynamics.



