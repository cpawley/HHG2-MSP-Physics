[<- Back to index page](https://cpawley.github.io/HHG2-MSP-Physics/)
# Tensors

---

## “A tensor is a mathematical object which transforms as a tensor”


---
uhh umm okay? Let us break it down!

---

The word tensor comes from the latin word tendere, which means “to stretch”. Tensile stress can be described as the stretching out of something. Tensors can measure how the three dimensions change (stretch) when one or more of them are changed. A tensor has this neat ability to remain a tensor and have the same physics occur even when is it transformed, that means when it changes coordinate systems. The math and values might change but the physics of it will not! Yes! As in no matter what reference frame (coordinate system) the object, occurance, field, particle being described by the tensor is in the same event will happen simply with different numberical values. One can think of it as the proportion or ratio to each other will chnage but it will alwyas be a whole. 

---

### Simple! Right>?>?

---

A tensor is a assebly of numerical values which hold their physical significance even after coordinate transformations. 


---
### okay but how is this measured and calculated?

---

First, perhaps a different definition:
A rank – _n_ tensor in _m_ – dimensions is a mathematical object that has: _n_ indices and _m<sup>n</sup>_ components and obeys “certain transformation rules”.  

Below is the set up of a tensor with _m_=4  _n_=2, with _4<sup>2</sup>_= 16 components: _refer back to this image for explanations further on_

### Stress-Energy Tensor 

![alt text](https://github.com/cpawley/HHG2-MSP-Physics/blob/Floris-Images/stresstensor.png?raw=true)


---

### hmm still a bit abstract…

---

The dimensions is represented by _m_. _m_ is simply the dimension of the matrix. (easy peazy)

3x3 matrix,  _m_=3

4x4 matrix,  _m_=4

The amount of components within a tensor is _m<sup>n</sup>_. What is _n_?

---

the infamous _n_ is... “rank”

For rank, _n_ signifies the parameters that are necessary to find what you are looking for, which is the component, within the mathematical object, which is a matrix. 
* matrix is a mathematical tool which can help in some scenarios organize numbers more understandable/workable  

Example: For a matrix which is RxR and neither R is 1, the parameter needed to find components within matrix are simply Row (look along the horizontal) and Column (look down the vertical) therefore there are 2 parameters, also called “rank 2”, by defenition: _n_=2. _n_ is the quantity of indices, here there would be two. 

If the matrix was Rx1, then n=1, because we would only need to look from one direction. While if the matrix changed to an IxJxK (a 3-d matrix) then there would be 3 parameters, n=3, three directions to search needed to find desired component. 

To apply this example, the above stress-energy tensor is a rank n=2 and a dimension m=4 tensor (4x4).

As we progress, and understand tensors better, we begin to use index notation. 
When the tensor symbol (usually a Greek letter) does not have an index it means it is rank 0, which means one doesn’t need any information to find a component – there is only one value attached to tensor….. so it is a scalar!

n=0: scalar. 

n=1: one piece of info, one index, necessary to find component, vector. Example velocity of a rolling ball on surface.

n=2: two pieces of information, two indices

Traditionally for 2- and 3-dimensions Latin letters are used. 4 dimensions and higher Greek letters are used. 

n=3: three indices

n=4: four indices 

and so on. 

Below is a depiction of indices! There can be more than one and can be in different positions. There are co- and contra- varients. 

<img src="https://github.com/cpawley/HHG2-MSP-Physics/blob/Floris-Images/Raquel_Indices.png?raw=true" width="600"/>




<img src="https://github.com/cpawley/HHG2-MSP-Physics/blob/Floris-Images/cocontra.png?raw=true"/>


<img src="https://github.com/cpawley/HHG2-MSP-Physics/blob/Floris-Images/Raquel_Cocontra.png?raw=true" width="600"/>





--- 
### a bit better??

---

Well now more on the physics of a tensor! 

A tensor can describe an object which can undergo stress. In other words it can be “moved”, either stretched or compressed, along the 3 spacial directions.

**BUT**, then also each side of the object can also undergo structural strain (6 more stresses) – therefore it can be said there are 9 possible stresses.  

<img src="https://github.com/cpawley/HHG2-MSP-Physics/blob/Floris-Images/rotation.png?raw=true" />


Forces **cannot** just be added along the 3-d because they are interacting differently; this is not classical mechanics. Each of the 9 forces makes the object “react in a different way”. A way to express this tensor is with a 3x3 matrix, m = 3. 

So then how many components total? _m<sup>n</sup>_ 

if there is a 4x4 matrix, _m_=4
and _n_=2 

_m<sup>n</sup>_ = _4<sup>2</sup>_ = 16 

It is the same as saying 4x4 = 16.. but if its a rank _n_=3, then there would be 3-d matrix (again m=4):  4x4x4 = _4<sup>3</sup>_ = 64


---
### Okay, okay I think I get it... but   

---

What makes them tensors?

* HOW THEY TRANSFORM! the COORDINATE SYSTEM TRANSFORMATION 
  * chosen coordinate system should and does not affect the physics of the situation

_Physical nature remains the same, although the components' numerical values might change._

Physical nature being what is happening physically, the state the object observed is in. 

Going back to the defenition which states tensors undergo "certain transformations", below is the *transformation!* 

<img src="https://github.com/cpawley/HHG2-MSP-Physics/blob/Floris-Images/Raquel_Tensor_transform.png?raw=true" width="600" />








Rank 2 tensor can not be visualized like a vector or an arrow, but it can be though of as a transformation between vectors.  
Velocity is a real vector. To explain a real vector: if a vector is zero in one coordinate system, for it to be a real vector, it should be zero in all coordinate systems.   
Velocity can be relative, for example a ball moves relative to the table but not relative to itself. 

* angular momentum is actually a psudo vector, because if the origin changes, the time can go to zero, therefore changing the actual physics not just the maths of this vector [magnetic field is also a psudovector]

---
 
### Ex: 

F=q(v x B+E)

 
<img src="https://github.com/cpawley/HHG2-MSP-Physics/blob/Floris-Images/fqbv.png?raw=true" />
 
The cross product with the  4-velocity will change the velocity of a charged particle into a force. 


# Tensors CONCLUSION
### It is a number or a collection of numbers which maintain its MEANING under coordinate transformations. The components of the tensor will change, but the physical nature will not (after coordinate transformation).

---
---

# Contractions

---

Below are some basic rules for contractions.

<img src="https://github.com/cpawley/HHG2-MSP-Physics/blob/Floris-Images/Raquel_Tensor_contraction(1).png?raw=true" width="600"/>


<img src="https://github.com/cpawley/HHG2-MSP-Physics/blob/Floris-Images/Raquel_Tensor_contraction(2).png?raw=true" width="600"/>





---

### References

* Notes from General Relativity MSP course


Nick Lucid. June 2015. _Advanced Theoretical Physics: A Historical Perspective._ 

[Link to buy book - ony $5.00 actually super useful book!](https://gumroad.com/l/ubSc)
 

[Good blog type summary](https://hackaday.com/2020/01/29/tensors-explained/)


and of course The WIKIPEDIA link of LIFE! 

[Tensors](https://en.wikipedia.org/wiki/Tensor)

[Electromagnetic Tensor](https://en.wikipedia.org/wiki/Electromagnetic_tensor)

[Maxwell Stress Tensor](https://en.wikipedia.org/wiki/Maxwell_stress_tensor)

[Stress-Energy Tensor](https://en.wikipedia.org/wiki/Stress%E2%80%93energy_tensor)


### Video Links 

[The Science Asylum!](https://www.youtube.com/watch?v=bpG3gqDM80w)

[Dan Fleisch - With PROPS!](https://www.youtube.com/watch?v=f5liqUk0ZTw)

[Tensors Explained Intuitively: Covariant, Contravariant, Rank](https://www.youtube.com/watch?v=CliW7kSxxWU)


### Sample Exercises and Solutions


[1- Drexel University](https://www.math.drexel.edu/~dws57/Tensor_Calc_and_Moving_Surfaces_Exercises_New.pdf)

[2 - Heidelberg University](http://www.ita.uni-heidelberg.de/~dullemond/lectures/tensor/tensor.pdf)



