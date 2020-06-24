# **Lagrangian Mechanics**

Newton's laws of motion are the foundation on which all of classical mechanics, from celestial mechanics to rotational motion, to the ideal gas law, is based. However, identifying all the forces between objects creates difficulties when applying the Newtonian algorithm.
While vector quantities, in which Newton’s laws are described, can be rewritten in any coordinate system to simplify this problem, it is not the ideal option. 

This calls for a different coordinate system to simplify calculations.
 

It would be useful if the important quantities could be easily rewritten in the more optimal coordinate system and then solved. This can be done by describing our systems in terms of scalars instead of vectors. Scalars are quantities, such as mass or energy, that are described by a number or magnitude alone – and therefore are the same in any coordinate system. This concept is known as Langrangian (mechanics).
 
 
To clarify why this system is helpful, take a brief look at some challenging problems for the Newtonian approach:

### **Mass on a sliding wedge**

Imagine we have a block-shaped mass on a sliding wedge. Both the block and the wedge are free to move without friction under the force of gravity.
![Image of mass on a sliding wedge](https://ds055uzetaobb.cloudfront.net/brioche/uploads/3Q6ItWBg5y-screen-shot-2015-08-21-at-84207-pm.png?width=2000)

Setting this problem up is difficult for two reasons.
1. The mass MM moves along the floor while mm moves at an angle, which creates a tension in the choice of coordinates (the Cartesian grid in the frame of the ground, and another in the frame of the tilted surface).
2. The second is that the normal force between MM and mm depends upon the motion of MM and mm.
 
### **Bead on a spinning hoop**

Consider a bead that is free to slide on a rotating hoop. This is difficult to describe in vectors because gravity calls for Cartesian coordinates, but the constraint of the hoop suggests polar coordinates. Deciding on a uncomplicated representation is difficult.

![Image of a bead on a spinning hoop](https://ds055uzetaobb.cloudfront.net/brioche/uploads/Jg7mhai6ay-screen-shot-2015-08-21-at-92015-pm.png?width=600)

### **Coupled pendulums**

Lastly, the coupled pendulum: where one pendulum hangs from the end of another. Between the coupling of the two pendulums, and the constraint that keeps the two pendulums from breaking apart, the choice of representation is not straightforward.
 
 

The standard of identifying forces, writing down constraints, converting to a useful system of coordinates, and substituting to uncouple equations does not work easily here.


## Problems with the Newtonian approach

To see why Langrangian is needed, we must explore the problems with Newtonian mechanics.

- **Vector representation**: We run into trouble using vectors when we need to switch coordinate systems.
  - Though we can write the force of gravity as *-gẑ* in a Cartesian coordinate system, it’s easier to describe the pendulum swing in terms of the angle *θ*. Rewriting the acceleration vector of the pendulum bob is unnecessarily difficult. It only gets worse in more complex problems.
Contrast this to the ease with which we can transform scalar quantities such as the kinetic energy K.E. = *½ mv2 → ½ mω^2r + ½ m(r’)2*. A system without vectors would be useful.

- __Identifying forces__: In using Newton's laws, we must account for all forces as well as their counter forces. When there is more than one particle, this can lead to many incompatibly described forces. Life, or at least complex systems, would be easier without vector forces.

- __Constraints__: Newtonian mechanics needs explicit constraints in the equations of motion, which can quickly become very complicated, especially when constraints are imposed by non-rigid surfaces. Langrangian imposes constraint implicitly by the choice of coordinates.



We aim to reshape mechanics in an energy-based, vector-free manner. 
## How?

Newton's second law states that the acceleration of any particle is given by the net force upon the particle, where the acceleration and net force are both vectors in one, two, or three dimensions:
 
We recall the work-energy principle which states that the work done by the net force (i.e. the non-constraint forces) on a particle is equal to the increase in kinetic energy of the particle. We ignore constraint forces because they always act perpendicular to the direction of motion, and thus perform no work on systems.

:thinking:

