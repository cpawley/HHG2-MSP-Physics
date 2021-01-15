[<- Back to index page](https://cpawley.github.io/HHG2-MSP-Physics/)

# Differentiation 

[create an anchor](## Overview-of-Differentiation) 
#### Different notations 
#### Important Differentiation Rule 
#### Rules for Combined Functions 
#### Applications of Derivatives to Real Life 
#### Glossary 
#### Exercises 
#### Additional Video Links

(## Overview-of-Differentiation)

Differentiation is, by definition, the way to find a function that represents the rate of change of one variable with respect to another variable. To begin simply, we will take a variable that changes across time, like a car traveling along a road for a defined amount of time. By differentiating this, we can find the velocity. By further differentiating that, the acceleration can be found. Why this is will be further discussed below:

The primary motivation for understanding and using differentiation was the tangent line problem, that is, for a curved graph, what is the slope that is tangent to it at a given point. Thus, by solving the slope of the curve at that point, the tangent problem can be solved. In many cases finding the slope may be easy. If a graph has the equation y=mx+b, m already represents the slope. It becomes more difficult if your graph follows an equation similar to y=cos(x)+x3at x=2. 

The next step involves understanding what the slope is, and how it can be rewritten to something that looks like a differentiation. The slope/gradient of a curve is commonly expressed as “rise over run” where over a straight line finite line, the slope can be expressed as the total distance it travels over the y-axis (the rise) divided by the total distance it travels with respect to the x-axis (the run). In other words, it is the change of variables within the y-axis divided by the change in variables in the x-axis. This change is known as delta (Δ). Going back to the example of the car going down a road, if it travels 30 metres in 5 seconds, and we take the distance to be the y-axis and the time to be the x-axis, then the slope represents 305m/sor 6m/s; the velocity. 

It won't always be as easy as this though, as most graphs in physics are curved, which makes getting the slope much harder to get. In this way, a tangential line is used to represent the slope at a given point. The definition of a tangent is something that only just touches the line, such as in the image below. The point that it intersects at is infinitesimally small, and will from now on be referred to as “d” instead of delta (which represents a finite difference). Therefor, the slope at a tangential point on the graph of position versus time will be written as dxdt; a differentiation. 

## Different Notations:

In many study materials, you will encounter variations of the notations of derivatives. These different notations are denoted below, so you can recognise them.

> **Leibniz’s notation:** dydxordfdx or ddxf for the first derivative of a function y or f dependent    on x. The second derivatives are d2ydx2,d2fdx2, d2dx2f and  respectively.
 
> **Lagrange’s notation:** f’ for the first derivative and f’’  for the second derivative (any    
derivative beyond the third derivative - f’’’ - is denoted as fnfor the nth derivative).

> **Newton’s notation:** ẏ for the first derivative and ÿ for the second.

> **Euler’s notation:** Dxyor Dxf(x)for the first derivative; Dxnf(x)  for the nth derivative.

## Important Differentiation Rules:

When a function is derived with respect to a variable, this general rule applies for finding the derivative:
For *f(x) = axn→ f’(x) = naxn-1**

## Rules for Combined Functions:

>- **Constant rule*: If a function f(x) is constant, then its derivative is zero.
*f(x) = c where c is a constant, then: f’(x) = 0.*

>- **Sum rule:** When a function f is the summation of two functions g and h, then the derivative of f is equal to the sum of the derivatives of g and h.
*f = αg + βh →  f’ = (αg + βh)’ = αg’ + βh’.*

>- **Product rule:** When a function f is the product of two functions g and h, the derivative of f is the summation of the product of g and h’ and the product of g’ and h.
*f = gh →  f’ = gh’ + g’h.*

>- **Quotient rule:** This slightly more difficult rule is used to find the derivative of a function f that is the quotient of two functions g and h.
*f = gh→  f’ = g'h-gh'h2*

>- **Chain rule:** This rule is used for composite functions, like, for example f(x) = h(g(x)). So, h is a function of g and g in turn is a function of x. The derivative of such a composite function is:
*f’(x) = h’(g(x))g’(x).*

## Applications of derivatives in real life

*Business:* in business, differentiation is used to determine the profit and loss using graphs.
*Optimisation:* in optimisation, differentiation is used on many occasions. Say, for example, you have a limited amount of material to produce a cylinder that holds liquid. Differentiation can help you to find out how to use the material to make a cylinder that is capable of holding the maximum amount of liquid.
*Physics:* by using differentiation, a moving body’s position allows you to calculate its velocity and acceleration.
*Chemistry:* in chemistry, the change in concentration of an element during a chemical reaction can be estimated using differentiation. Additionally, the rate of the reaction is found using derivatives.

Below is a list of common derivatives.

<img align= "center"  src="https://github.com/cpawley/HHG2-MSP-Physics/blob/master/SadVries_images/Derrivatives 1.png?raw=true">

Sometimes, it can be hard to imagine how a certain graph looks yet having an image in mind may prove to be useful when working with derivatives. Below are a few graphs corresponding to some standard derivatives.

<img align= "left"  src="https://github.com/cpawley/HHG2-MSP-Physics/blob/master/SadVries_images/image 2.png?raw=true">

<img align= "right"  src="https://github.com/cpawley/HHG2-MSP-Physics/blob/master/SadVries_images/image 3.png?raw=true">

**Graph 1**: y = -sin(x) which is the derivative of the cosine function. **Graph 2**: y = 1/x which is the derivative of the natural logarithm (ln).

<img align= "right"  src="https://github.com/cpawley/HHG2-MSP-Physics/blob/master/SadVries_images/image 4.png?raw=true">

**Graph 3**: y is a cubic function, which is the derivative of a fourth-degree polynomial.

## Glossary

*Derivative:* a measurement of the rate of change of a function with respect to a variable. Derivatives are one of the fundamental tools for calculus.

*Differentiation:* the operation of finding the derivative of a function.

*Gradient/slope:* a number describing the direction and steepness of a function. For a straight line, the slope is equal to the distance travelled over the y-axis divided by the distance travelled over the x-axis. For curved graphs, the slope at a certain point is equal to the derivative at that point.

*Tangent:* a straight line (or plane) that, at a certain point, touches a curve but does not cross it at that point.

<span style="background-color:yellow">
## Sample exercises
Compute the following derivatives:
1.     f(x) = 4x4 + 3x2 + 1
2.     f(x) = x sin(2x)
3.     f(x) = exx2
4.     f(x) = ln(x2)
</span>
  
<span style="background-color:light-yellow">
Answers:
1. f’(x) = 16x3 + 6x
2. f’(x) = sin(2x) + 2xcos(2x) 	                                                                         Product + Chain rules
3. f’(x) = x2ex-2xexx4 = xex(x-2)x4= ex(x-2)x3                                                        Quotient rule
4. f’(x) = 1x22x =2x            
</span>

## Videos on Rules for Combined Functions: 

**For an explanation and examples of the Product Rule:** 

[![Product Rule](http://img.youtube.com/vi/B28EXpofKy4/0.jpg)](https://www.youtube.com/watch?v=B28EXpofKy4 "For an explanation and examples of the product rule")


**For an explanation and examples of the quotient rule:**


[![Quotient Rule](http://img.youtube.com/vi/O6M4O7zY5eA/0.jpg)](https://www.youtube.com/watch?v=O6M4O7zY5eA "For an explanation and examples of the quotient rule)


**For an explanation on when and how to use the chain rule:**


[![Chain Rule](http://img.youtube.com/vi/H-ybCx8gt-8/0.jpg)](https://www.youtube.com/watch?v=H-ybCx8gt-8"For an explanation and examples of the chain rule)

