# **Lagrangian Mechanics**

Newton's laws of motion are the foundation on which all of classical mechanics, from celestial mechanics to rotational motion, to the ideal gas law, is based. However, identifying all the forces between objects creates difficulties when applying the Newtonian algorithm.
While vector quantities, in which Newton’s laws are described, can be rewritten in any coordinate system to simplify this problem, it is not the ideal option. 

This calls for a different coordinate system to simplify calculations.
 

It would be useful if the important quantities could be easily rewritten in the more optimal coordinate system and then solved. This can be done by describing our systems in terms of scalars instead of vectors. Scalars are quantities, such as mass or energy, that are described by a number or magnitude alone – and therefore are the same in any coordinate system. This concept is known as Langrangian (mechanics).

 
To clarify why this system is helpful, take a brief look at some challenging problems for the Newtonian approach:

<br>

### **Mass on a sliding wedge**

Imagine we have a block-shaped mass on a sliding wedge. Both the block and the wedge are free to move without friction under the force of gravity.

![Image of mass on a sliding wedge](https://raw.githubusercontent.com/cpawley/HHG2-MSP-Physics/master/Fenora%20images/mass%20blocks.png)

Setting this problem up is difficult for two reasons.
1. The mass MM moves along the floor while mm moves at an angle, which creates a tension in the choice of coordinates (the Cartesian grid in the frame of the ground, and another in the frame of the tilted surface).
2. The second is that the normal force between MM and mm depends upon the motion of MM and mm.

<br> 
 
### **Bead on a spinning hoop**

Consider a bead that is free to slide on a rotating hoop. This is difficult to describe in vectors because gravity calls for Cartesian coordinates, but the constraint of the hoop suggests polar coordinates. Deciding on a uncomplicated representation is difficult.

![Image of a bead on a spinning hoop](https://raw.githubusercontent.com/cpawley/HHG2-MSP-Physics/master/Fenora%20images/bead%20on%20wire.png)

<br>

### **Coupled pendulums**

Lastly, the coupled pendulum: where one pendulum hangs from the end of another. Between the coupling of the two pendulums, and the constraint that keeps the two pendulums from breaking apart, the choice of representation is not straightforward.
 
 

The standard of identifying forces, writing down constraints, converting to a useful system of coordinates, and substituting to uncouple equations does not work easily here.

<br>

## Problems with the Newtonian approach

To see why Langrangian is needed, we must explore the problems with Newtonian mechanics.

- **Vector representation**: We run into trouble using vectors when we need to switch coordinate systems.
  - Though we can write the force of gravity as *-gẑ* in a Cartesian coordinate system, it’s easier to describe the pendulum swing in terms of the angle *θ*. Rewriting the acceleration vector of the pendulum bob is unnecessarily difficult. It only gets worse in more complex problems.
Contrast this to the ease with which we can transform scalar quantities such as the kinetic energy:

![1](https://raw.githubusercontent.com/cpawley/HHG2-MSP-Physics/master/Fenora%20images/1.jpg)

<!--  K.E. = \frac{1}{2} m v^{2} \rightarrow   \frac{1}{2} m  \omega^{2} r + \frac{1}{2} m \dot{r}^{2} --> 

A system without vectors would be useful.

- __Identifying forces__: In using Newton's laws, we must account for all forces as well as their counter forces. When there is more than one particle, this can lead to many incompatibly described forces. Life, or at least complex systems, would be easier without vector forces.

- __Constraints__: Newtonian mechanics needs explicit constraints in the equations of motion, which can quickly become very complicated, especially when constraints are imposed by non-rigid surfaces. Langrangian imposes constraint implicitly by the choice of coordinates.



We aim to reshape mechanics in an energy-based, vector-free manner. 

<br>

# How to reformulate mechanics?

Newton's second law states that the acceleration of any particle is given by the net force upon the particle, where the acceleration and net force are both vectors in one, two, or three dimensions:

![newtons 2nd law](https://raw.githubusercontent.com/cpawley/HHG2-MSP-Physics/master/Fenora%20images/2.jpg)


Remember the work-energy principle?  It states that the work done by the net force (i.e. the non-constraint forces) on a particle is equal to the increase in kinetic energy of the particle. We don’t pay attention to constraint forces because they always act perpendicular to the direction of motion, and as such perform no work on systems.


Think about an arbitrary, infinitesimal displacement ![10](https://raw.githubusercontent.com/cpawley/HHG2-MSP-Physics/master/Fenora%20images/10.jpg)<!-- \delta\vec{r}δr--> of the position of our particle under the net force. We can say ![3](https://raw.githubusercontent.com/cpawley/HHG2-MSP-Physics/master/Fenora%20images/3.jpg) <!-- \vec{F}\cdot \delta\vec{r} = m\vec{a}\cdot\delta\vec{r}F⋅δr=ma⋅δr --> . If we integrate along a finite displacement, we find that

![4](https://raw.githubusercontent.com/cpawley/HHG2-MSP-Physics/master/Fenora%20images/4.jpg)<!-- W = \int \vec{F}_\text{net} \cdot \delta\vec{r}W=∫Fnet​⋅δr -->

and therefore


![5](https://raw.githubusercontent.com/cpawley/HHG2-MSP-Physics/master/Fenora%20images/5.jpg)<!-- \int \left(\vec{F}_\text{net}-m\vec{a}\right)\cdot \delta\vec{r} = 0.∫(Fnet​−ma)⋅δr=0 -->.


This statement is known as d'Alembert's principle and is where we begin to  reform Newtonian mechanics so that it erases the problems we discussed above.

<br>

## Eliminating _Forces_

Our first issue is to swap vector forces for scalar energies. Remember that conservative forces are those that can be written as the spatial derivative of a potential function, i.e.

![6](https://raw.githubusercontent.com/cpawley/HHG2-MSP-Physics/master/Fenora%20images/6.jpg) <!-- F_i = -\frac{\partial V(r_1, \ldots, r_n)}{\partial r_i}.Fi​=−∂ri​∂V(r1​,…,rn​)​.-->

While at the lowest level, namely particle interactions, all forces are conservative, when we consider the macroscopic we often approximate conservative forces between particles with dissipative forces (e.g. contact friction or viscosity).

At the moment, let’s deal with conservative forces; we’ll think about dissipative forces later.

First, we rewrite Newton's second law ![7](https://raw.githubusercontent.com/cpawley/HHG2-MSP-Physics/master/Fenora%20images/7.jpg)<!-- \vec{F} = m\ddot{\vec{r}}F=mr¨--> as

![8](https://raw.githubusercontent.com/cpawley/HHG2-MSP-Physics/master/Fenora%20images/8.jpg)<!-- m\ddot{\vec{r}} \cdot \delta\vec{r} = - \frac{\partial V(\vec{r})}{\partial \vec{r}}\cdot \delta\vec{r} = - \big[\nabla_r V(\vec{r})\big] \cdot \delta\vec{r}.mr¨⋅δr=−∂r∂V(r)​⋅δr=−[∇r​V(r)]⋅δr. -->

<br>

## Getting rid of _Vectors_ and introducing _Energy_
In the rewriting above, we’ve gotten rid of forces by relating the spatial derivatives of the potential energy to the acceleration vector. Problem: we still have vectors.

Next, we want to erase anything containing derivatives of position vectors and swap them with derivatives of scalar quantities like energy. This will eliminate our dependence on vector quantities to represent positions and velocities.

We move on from the statement of d'Alembert's principle

![9](https://raw.githubusercontent.com/cpawley/HHG2-MSP-Physics/master/Fenora%20images/9.jpg)<!-- \vec{F}_\text{net} \cdot \delta\vec{r} = m\frac{d^2\vec{r}}{dt^2} \cdot \delta\vec{r},Fnet​⋅δr=mdt2d2r​⋅δr, -->

where ![10](https://raw.githubusercontent.com/cpawley/HHG2-MSP-Physics/master/Fenora%20images/10.jpg)<!-- \delta \vec{r}δr --> is some infinitesimal movement of the particle. Immediately, we can rewrite the right-hand side as

![11](https://raw.githubusercontent.com/cpawley/HHG2-MSP-Physics/master/Fenora%20images/11.jpg)<!-- m\left[ \frac{d}{dt}\left( \frac{d\vec{r}}{dt}\cdot \delta\vec{r} \right) - \frac{d\vec{r}}{dt}\cdot\frac{d\delta\vec{r}}{dt}\right],m[dtd​(dtdr​⋅δr)−dtdr​⋅dtdδr​], -->

where we have applied the identity ![12](https://raw.githubusercontent.com/cpawley/HHG2-MSP-Physics/master/Fenora%20images/12.jpg)<!-- \left(xy\right)^\prime = x^\prime y + y^\prime x(xy)′=x′y+y′x. -->

Above, we have an equation for the vector ![vector r](https://github.com/cpawley/HHG2-MSP-Physics/blob/master/Fenora%20images/vector%20r.jpg?raw=true)<!-- \vec{r}r --> that doesn’t reference a particular choice of coordinates, no Cartesian or spherical, etc.. We now expand the RHS in a coordinate basis ![13](https://raw.githubusercontent.com/cpawley/HHG2-MSP-Physics/master/Fenora%20images/13.jpg)<!-- r_1, \ldots, r_n:r1​,…,rn​ --> :

![14](https://raw.githubusercontent.com/cpawley/HHG2-MSP-Physics/master/Fenora%20images/14.jpg)<!-- \begin{aligned} &m\sum_k\left[\frac{d}{dt}\left( \frac{d\vec{r}}{dt}\cdot \frac{\partial \vec{r}}{\partial r_k}\delta r_k \right) - \frac{d\vec{r}}{dt}\cdot\frac{\partial\dot{\vec{r}}}{\partial r_k} \delta r_k\right] \\ =& m\sum_k\left[\frac{d}{dt}\left( \dot{\vec{r}}\cdot \frac{\partial \vec{r}}{\partial r_k}\right) - \dot{\vec{r}}\cdot\frac{\partial\dot{\vec{r}}}{\partial r_k} \right]\delta r_k. \end{aligned}=​mk∑​[dtd​(dtdr​⋅∂rk​∂r​δrk​)−dtdr​⋅∂rk​∂r˙​δrk​]mk∑​[dtd​(r˙⋅∂rk​∂r​)−r˙⋅∂rk​∂r˙​]δrk​.​ -->

Now, for any ![vector r](https://github.com/cpawley/HHG2-MSP-Physics/blob/master/Fenora%20images/vector%20r.jpg?raw=true)<!-- \vec{r}r -->, we have the following identity, known as dot-cancellation: 

<br>

## _Dot-cancellation_ theorem

_If we expand a vector ![vector r](https://github.com/cpawley/HHG2-MSP-Physics/blob/master/Fenora%20images/vector%20r.jpg?raw=true)<!-- \vec{r}r --> in any coordinate basis ![13](https://raw.githubusercontent.com/cpawley/HHG2-MSP-Physics/master/Fenora%20images/13.jpg) <!-- \{r_1,\ldots,r_n\}{r1​,…,rn​} -->, we have_

![15](https://raw.githubusercontent.com/cpawley/HHG2-MSP-Physics/master/Fenora%20images/15.jpg)<!-- \frac{\partial \vec{r}}{\partial r_k} = \frac{\partial \dot{\vec{r}}}{\partial \dot{r}_k}.∂rk​∂r​=∂r˙k​∂r˙​ -->.




Using this identity, the right-hand side becomes

![16](https://raw.githubusercontent.com/cpawley/HHG2-MSP-Physics/master/Fenora%20images/16.jpg)<!-- m\sum_k\left[\frac{d}{dt}\left( \dot{\vec{r}}\cdot \frac{\partial \dot{\vec{r}}}{\partial \dot{r}_k}\right) - \dot{\vec{r}}\cdot\frac{\partial\dot{\vec{r}}}{\partial r_k} \right]\delta r_k.mk∑​[dtd​(r˙⋅∂r˙k​∂r˙​)−r˙⋅∂rk​∂r˙​]δrk​. -->

Recognizing ![17](https://raw.githubusercontent.com/cpawley/HHG2-MSP-Physics/master/Fenora%20images/17.jpg)<!-- \dot{\vec{r}} = \vec{v}r˙=v --> , we rewrite this as

![18](https://raw.githubusercontent.com/cpawley/HHG2-MSP-Physics/master/Fenora%20images/18.jpg)<!-- \begin{aligned} &m\sum_k\left[\frac{d}{dt}\left(\frac12 \frac{\partial v^2}{\partial \dot{r}_k}\right) - \frac12 \frac{\partial v^2}{\partial r_k} \right]\delta r_k \\ &=\sum_k\left[\frac{d}{dt}\left(\frac{\partial T}{\partial \dot{r}_k}\right) - \frac{\partial T}{\partial r_k} \right]\delta r_k, \end{aligned}​mk∑​[dtd​(21​∂r˙k​∂v2​)−21​∂rk​∂v2​]δrk​=k∑​[dtd​(∂r˙k​∂T​)−∂rk​∂T​]δrk​,​ -->

where in the second line we've made the replacement ![19](https://raw.githubusercontent.com/cpawley/HHG2-MSP-Physics/master/Fenora%20images/19.jpg)<!-- \frac12 mv^2.T=21​mv2. -->

Thus

![20](https://raw.githubusercontent.com/cpawley/HHG2-MSP-Physics/master/Fenora%20images/20.jpg)<!-- \begin{aligned} - \sum_k \frac{\partial V}{\partial r_k} \delta r_k &= \sum_k\left[\frac{d}{dt}\left(\frac{\partial T}{\partial \dot{r}_k}\right) - \frac{\partial T}{\partial r_k} \right] \delta r_k \\ 0 &= \sum_k\left[\frac{d}{dt}\left(\frac{\partial T}{\partial \dot{r}_k}\right) - \frac{\partial T}{\partial r_k} + \frac{\partial V}{\partial r_k} \right] \delta r_k . \end{aligned}−k∑​∂rk​∂V​δrk​0​=k∑​[dtd​(∂r˙k​∂T​)−∂rk​∂T​]δrk​=k∑​[dtd​(∂r˙k​∂T​)−∂rk​∂T​+∂rk​∂V​]δrk​.​ -->
Now, remember that the small displacement ![21](https://raw.githubusercontent.com/cpawley/HHG2-MSP-Physics/master/Fenora%20images/21.jpg)<!-- \delta \vec{r}δr--> was arbitrary. In three dimensions, we could have ![22](https://raw.githubusercontent.com/cpawley/HHG2-MSP-Physics/master/Fenora%20images/22.jpg)<!--\delta\vec{r} = \langle \delta_x, 0, \delta_z \rangleδr=⟨δx​,0,δz​⟩ or \langle 0, 0, \delta_z \rangle⟨0,0,δz​⟩-->. But the equation must be true independent of the displacement, i.e. every term in the sum is equal to zero independent of the coordinate displacements ![23](https://raw.githubusercontent.com/cpawley/HHG2-MSP-Physics/master/Fenora%20images/23.jpg)<!-- \delta r_k.δrk​-->. Therefore, we have
![24](https://raw.githubusercontent.com/cpawley/HHG2-MSP-Physics/master/Fenora%20images/24.jpg)<!-- 0 = \frac{d}{dt}\left(\frac{\partial T}{\partial \dot{r}_k}\right) + \frac{\partial\left(V - T\right)}{\partial r_k}0=dtd​(∂r˙k​∂T​)+∂rk​∂(V−T)​ -->
for each _k_.
For conservative forces, _V_ is a pure function of the position variables so that ![25](https://raw.githubusercontent.com/cpawley/HHG2-MSP-Physics/master/Fenora%20images/25.jpg)<!--\frac{\partial V}{\partial \dot{r}_k}=0∂r˙k​∂V​=0-->. We can therefore move _V_ into the derivative and write

![26](https://raw.githubusercontent.com/cpawley/HHG2-MSP-Physics/master/Fenora%20images/26.jpg)<!--\frac{\partial\left(T - V\right)}{\partial r_k} = \frac{d}{dt}\frac{\partial \left(T-V\right)}{\partial \dot{r}_k}.∂rk​∂(T−V)​=dtd​∂r˙k​∂(T−V)​-->.

In doing the above reformation, we have removed position and velocity vectors entirely from classical mechanics. If we call the difference between the kinetic energy and the potential energy _L= T - VL = T − V_, we can shorten our equation to

![27](https://raw.githubusercontent.com/cpawley/HHG2-MSP-Physics/master/Fenora%20images/27.jpg)<!--\frac{\partial L}{\partial r_k} = \frac{d}{dt}\frac{\partial L}{\partial \dot{r}_k} .∂rk​∂L​=dtd​∂r˙k​∂L​-->.

The quantity _T - VT − V_ is called the Lagrangian of the system, and the equation for _L_ is called the Euler equation. In any problem of interest, we obtain the equations of motion in a straightforward manner by evaluating the Euler equation for each variable. For example, in a spherical coordinate system, we would have three Euler equations for _r_, _θ_, and _ϕ_.

_The Lagrangian_, L, _of a system is the difference of the kinetic energy_ T _and the potential energy_ V _:_
![29](https://raw.githubusercontent.com/cpawley/HHG2-MSP-Physics/master/Fenora%20images/29.jpg)<!-- L(r, \dot{r}) \equiv T(r, \dot{r}) - V(r).L(r,r˙)≡T(r,r˙)−V(r)-->.

<br>

## Implicit Constraints

Our final aim was to remove the explicit inclusion of constraint forces. But actually, in eliminating forces, we’ve also eliminated constraint forces. We removed them when we introduced d’Alembert’s principle. In the Lagrangian formulation, constraints can be incorporated in several ways; we'll focus on the simplest:

When we chose coordinates over vectors, not only did we eliminate vectors, but we restated mechanics in terms of generalised coordinates. This means we can pick any coordinate system to describe our system. 

If a particle is constrained to move on the surface of a sphere, we can use a spherical coordinate system where _r_ is held constant. In other words, we are including constraints intrinsically through our choice of coordinates!

<br>

## Some Solved Problems

That’s a lot of text, with no real use for it. It might be clearer once we apply this Langrangian formulation to actual problems.

<br>

### Mass on an inclined plane

Because the mass slips down the inclined plane, we can choose our coordinate to be the distance along the plane _s_. In this coordinate system, the kinetic energy of the mass is given by ![30](https://raw.githubusercontent.com/cpawley/HHG2-MSP-Physics/master/Fenora%20images/30.jpg)<!--T=\frac12 m \dot{s}^2T=21​ms˙2-->. If we define the initial potential energy to be zero, then the potential energy as a function of _s_ is given by ![31](https://raw.githubusercontent.com/cpawley/HHG2-MSP-Physics/master/Fenora%20images/31.jpg)<!--V=+mgs\sin\thetaV=+mgssinθ-->, where _θ_ is the angle of the incline. 

Thus our Lagrangian is given by

![32](https://raw.githubusercontent.com/cpawley/HHG2-MSP-Physics/master/Fenora%20images/32.jpg)<!--L = \frac12 m \dot{s}^2 - mgs\sin\theta.L=21​ms˙2−mgssinθ-->.

As _s_ is the only variable coordinate in this problem, we have one Euler equation to consider:

![33](https://raw.githubusercontent.com/cpawley/HHG2-MSP-Physics/master/Fenora%20images/33.jpg)<!--\begin{aligned} \frac{d}{dt}\frac{\partial L}{\partial \dot{s}} &= \frac{\partial L}{\partial s} \\ m\frac{d}{dt}\dot{s} &= - mg\sin\theta \\ m\ddot{s} &= - mg\sin\theta\\ \ddot{s} &= - g\sin\theta, \end{aligned}dtd​∂s˙∂L​mdtd​s˙ms¨s¨​=∂s∂L​=−mgsinθ=−mgsinθ=−gsinθ-->,

Above is the equation of motion we expect for the mass on an inclined plane. This solution may have been surprisingly simple: upon writing down the kinetic and potential energies, the solution is just taking some derivatives.

<br>

### Celestial mechanics

Imagine we have a star of mass _M_ with a much greater mass than our planet of mass _m_. The planet and star interact through the gravitational potential ![34](https://raw.githubusercontent.com/cpawley/HHG2-MSP-Physics/master/Fenora%20images/34.jpg)<!--V(r) = -GMm/r,V(r)=−GMm/r-->, where _r_ is the distance separating the star and planet. What are the equations of motion?

Given the symmetry of the problem, it’s easiest to write in polar coordinates, with _r_ being the distance between the star and the planet, and _θ_ the angle of our planet around its orbit.

The kinetic energy of the planet is given by ![35](https://raw.githubusercontent.com/cpawley/HHG2-MSP-Physics/master/Fenora%20images/35.jpg)<!--T = \frac12 m \dot{r}^2 + \frac12 m \left(r\dot{\theta}\right)^2T=21​mr˙2+21​m(rθ˙)2-->.

Thus our Lagrangian is given by

![36](https://raw.githubusercontent.com/cpawley/HHG2-MSP-Physics/master/Fenora%20images/36.jpg)<!--L = \frac12 m \dot{r}^2 + \frac12 m \left(r\dot{\theta}\right)^2 + GMm/r.L=21​mr˙2+21​m(rθ˙)2+GMm/r-->.

Both _r_ and _θ_ can vary, so we have two Euler equations to set up. The one for _r_ is given by

![37](https://raw.githubusercontent.com/cpawley/HHG2-MSP-Physics/master/Fenora%20images/37.jpg)<!--\begin{aligned} \frac{d}{dt}\frac{\partial L}{\partial \dot{r}} &= \frac{\partial L}{\partial r} \\ m\ddot{r} &= mr\dot{\theta}^2 - GMm/r^2, \end{aligned}dtd​∂r˙∂L​mr¨​=∂r∂L​=mrθ˙2−GMm/r2-->,​

which is the equation of motion we expect for _r_.

For _θ_ we have

![38](https://raw.githubusercontent.com/cpawley/HHG2-MSP-Physics/master/Fenora%20images/38.jpg)<!--\begin{aligned} \frac{d}{dt}\frac{\partial L}{\partial \dot{\theta}} &= \frac{\partial L}{\partial \theta} \\ \frac{d}{dt}\left(mr^2\dot{\theta}\right) &= 0. \end{aligned}dtd​∂θ˙∂L​dtd​(mr2θ˙)​=∂θ∂L​=0-->.​

The Euler equation for \thetaθ reveals something interesting: the quantity in parentheses, the angular momentum of the planet, is a constant of the motion. We didn’t need to handle anything to do with torque or angular momentum, but we still found a conserved quantity. Finding a conserved quantity from our Euler equation is a feature of Lagrangian mechanics.

Before stating the general connection between the form of a Lagrangian and the conserved quantities of motion, we can make a further observation about our Lagrangian formalism.

<br>

### Generalized Momenta and Conservation

Kinetic energy, in Cartesian coordinates, is given by ![39](https://raw.githubusercontent.com/cpawley/HHG2-MSP-Physics/master/Fenora%20images/39.jpg)<!--T = \frac12 m \dot{r}^2T=21​mr˙2-->. 

Since potentials are functions of position, the velocity ![dot r](https://github.com/cpawley/HHG2-MSP-Physics/blob/master/Fenora%20images/dot%20r.jpg?raw=true)<!--\dot{r}r˙--> will only ever appear in the kinetic energy term. Thus, the quantity ![40](https://raw.githubusercontent.com/cpawley/HHG2-MSP-Physics/master/Fenora%20images/40.jpg)<!--\frac{\partial L}{\partial \dot{r}}∂r˙∂L​--> in the Euler equation will always be equal to ![41](https://raw.githubusercontent.com/cpawley/HHG2-MSP-Physics/master/Fenora%20images/41.jpg)<!--m\dot{r}mr˙-->. However, this is just the momentum of the particle. Thus, we can say that ![42](https://raw.githubusercontent.com/cpawley/HHG2-MSP-Physics/master/Fenora%20images/42.jpg)<!--p_r = \frac{\partial L}{\partial \dot{r}}pr​=∂r˙∂L​-->, i.e. the momentum of the particle is just the derivative of the Lagrangian with respect to the velocity.

Thus, we can rewrite the Euler equation as

![43](https://raw.githubusercontent.com/cpawley/HHG2-MSP-Physics/master/Fenora%20images/43.jpg)<!--\frac{d}{dt}p_r = \frac{\partial V}{\partial r}.dtd​pr​=∂r∂V​-->.

Notice also, in the orbital mechanics example, that the second Euler equation produced ![44](https://raw.githubusercontent.com/cpawley/HHG2-MSP-Physics/master/Fenora%20images/44.jpg)<!--\frac{\partial L}{\partial \dot{\theta}} = mr^2\dot{\theta}∂θ˙∂L​=mr2θ˙-->, the angular momentum of the particle. Thus, we have ![45](https://raw.githubusercontent.com/cpawley/HHG2-MSP-Physics/master/Fenora%20images/45.jpg)<!--p_\theta = \frac{\partial L}{\partial \dot{\theta}}pθ​=∂θ˙∂L​-->, just as we had for linear momentum above.

In fact, it is generally the case that the partial derivative of the Lagrangian with respect to any velocity variable is equal to the generalized momentum associated with that variable.

Thus, we can rewrite the Lagrangian formulation as

![46](https://raw.githubusercontent.com/cpawley/HHG2-MSP-Physics/master/Fenora%20images/46.jpg)<!--\dot{p}_i = \frac{\partial L}{\partial r_i}.p˙​i​=∂ri​∂L​.-->

From this we state a conservation principle about Lagrangians.

<br>

### Noether's theorem for momenta

If the coordinate _r<sub>k</sub>_ does not appear in the Lagrangian of a system, then the corresponding momenta is a conserved quantity.

Suppose the coordinate _r<sub>k</sub>_ makes no appearances in the Lagrangian, then

![47](https://raw.githubusercontent.com/cpawley/HHG2-MSP-Physics/master/Fenora%20images/47.jpg)<!--\dot{p}_k = \frac{\partial L}{\partial r_k} = 0.p˙​k​=∂rk​∂L​=0-->.

Thus, in the example of orbital mechanics, we can see that the Lagrangian makes no reference to the angular variable _θ_, and thus the angular momentum does not vary in time.

<br>

# What have we just covered?

On this page, we've just discussed a short-coming in Newtonian methods when we deal with multiple coordinate systems. We identified the things we would like our new system to have, and then created a method incorporating them. Hopefully, it's now clear why we have Langrangian mechanics, and what kind of problems we solve using this method.

<br>

### External links

[A simple and very short explanation of a Langrangian function from Britannica encyclopedia](https://www.britannica.com/science/Lagrangian-function)


[For a good discussion on Quora about Langrangian mechanics (that at least starts in layman's terms before derailing)](https://www.quora.com/In-laymans-terms-what-is-a-Lagrangian?share=1)

[As ever, Khan Academy will take you through all the steps, from earlier multivariable calculas, to using Langrangian to solve constrained optimisation problems](https://www.khanacademy.org/math/multivariable-calculus/applications-of-multivariable-derivatives)

Many universities have resources online about Lagrangian mechanics, but there are many from which to choose.
[We suggest MIT's coursework.](https://ocw.mit.edu/courses/physics/8-09-classical-mechanics-iii-fall-2014/lecture-notes/)
