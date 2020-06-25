
# Tensors and Contractions

---

## Tensors:

“A tensor is a mathematical object which transforms as a tensor”

---
uhh umm okay? Let us break it down!

---

Tensor comes from the latin word “to stretch”. Tensile stress can be described as the feeling of stretching something out. This is what tensors can measure, the quantity sides/different dimensions change (stretch) when one of them is changed. A tensor has this neat ability to remain a tensor and have the same physics occur when is it transformed – when one changes its coordinate system. The math and values might change but the physics of it will not! 


---
### okay but how is this measured and calculated?

---

First, perhaps a different definition:
A rank – _n_ tensor in _m_ – dimensions is a mathematical object that has: _n_ indices and _m<sup>n</sup>_ components and obeys “certain transformation rules”.  

Below is the set up of a tensor with _m_=4  _n_=2, with _4<sup>2</sup>_= 16 components:

![alt text](https://github.com/cpawley/HHG2-MSP-Physics/blob/Floris-Images/stresstensor.png)


---

hmm still a bit abstract…

The dimensions, _m_ is the dimension (lol). M is simply the dimension of the matrix. 

3x3 matrix,  _m_=3

4x4 matrix,  _m_=4

The amount of components within a tensor is _m<sup>n</sup>_. What is _n_?

---

the infamous _n_ is... “rank”

For rank, n signifies the parameters that are necessary to find what you are looking for, the component, within the mathematical object, matrix. 
* (matrix is a mathematical tool which can help in some scenarios organize numbers more understandable/workable).  

Example: For a matrix which is RxR and neither R is 1, the parameter needed to find components within matrix are simply Row and Column (look at along row and down column) therefore there are 2 parameters (“rank 2”)  n=2. N is the quantity of indices, here there would be two. 
If the matrix was Rx1, then n=1, because we would only need to look from one direction. While if the matrix changed to an IxJxK (a 3-d matrix) then there would be 3 parameters, n=3, three directions to search needed to find desired component. 
For example, the electromagnetic tensor is a rank n=2 and a dimension m=4 tensor (4x4). (insert picture)

As we progress, and understands tensors better, we begin to use index notation. 
When the tensor symbol (usually a Greek letter) does not have an index it means it is rank 0, which means one doesn’t need any information to find a component – there is only one value attached to tensor….. it is a scalar!

n=0, scalar. 

n=1, one piece of info, one index, necessary to find component, vector. Example velocity of a rolling ball on surface.

n=2, two pieces of information, two indices

Traditionally for 2- and 3-dimensions Latin letters are used. 4 dimensions and higher Greek letters are used. 

n=3, three indices

n=4, four indices 

and so on. 

Below is a depiction of indices! There can be more than one and can be in different positions. There are co- and contra- varients. 

![alt text](https://github.com/cpawley/HHG2-MSP-Physics/blob/Floris-Images/Indices.png)



![alt text](https://github.com/cpawley/HHG2-MSP-Physics/blob/Floris-Images/cocontra.png)


![alt text](https://github.com/cpawley/HHG2-MSP-Physics/blob/Floris-Images/updown.png)





--- 
### a bit better??

---

Well now more on the physics of a tensor! 

A tensor can describe an object which can undergo stress, be “moved”, either stretched or compressed, along the 3 spacial directions. *BUT*, then also each side of the object can also undergo structural strain (6 more stresses) – therefore it can be said there are 9 possible stresses.  

![alt text](https://github.com/cpawley/HHG2-MSP-Physics/blob/Floris-Images/9s.png)


Forces can not just be added along the 3-d because they are interacting differently. Each of the 9 forces makes the object “react in a different way”. A way to express this tensor is with a 3x3 matrix, m = 3. 

So then how many components total? _m<sup>n</sup>_ 

if there is a 4x4 matrix, _m_=4
and _n_=2 

_m<sup>n</sup>_ = _4<sup>2</sup>_ = 16 

It is the same as saying 4x4 = 16.. but if its a rank _n_=3, then there would be 3-d matrix (again m=4):  4x4x4 = _4<sup>3</sup>_ = 64


---
### Okay, okay I think I get it... but   

---

What makes them tensors?

* HOW THEY TRANSFORM (COORDINATE SYSTEM TRANSFORMATION)
  * chosen coordinate system should and does not affect the physics of the situation

_Physical nature remains the same, although the components “amounts” might change._

Going back to the defenition which states tensors undergo "certain transformations", below is the transformation! 

![alt text](https://github.com/cpawley/HHG2-MSP-Physics/blob/Floris-Images/transform.png)








Rank 2 tensor can not be visualized like an vector, arrow, but it can be though of as a transformation between vectors.  
Velocity is a real vector. If a vector is zero in one coordinate system, for it to be a real vector, it should be zero in all coordinate systems.   
Velocity can be relative, the ball moves relative to the table but not relative to itself. 

angular momentum is actually a psudo vector, because if the origin changes, the time can go to zero, therefore changing the actual physics not just the maths of this vector) [magnetic field is also a psudovector]


Ex: 

F=q(v x B+E)

 
![alt text](https://github.com/cpawley/HHG2-MSP-Physics/blob/Floris-Images/fqbv.png)
 
The cross product with the  4-velocity will change the velocity of a charged particle into a force. 


# Tensors CONCULSION
It is a number or a collection of numbers which maintain its MEANING under coordinate transformations. The components of the tensor will change, but the physical nature will not (after coordinate transformation).

---
---

# Contractions

---

![alt text](https://github.com/cpawley/HHG2-MSP-Physics/blob/Floris-Images/contraction.png)


![alt text](https://github.com/cpawley/HHG2-MSP-Physics/blob/Floris-Images/MT.png)





---





