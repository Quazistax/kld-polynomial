kld-polynomial
==============

A class of simple polynomial functionality including root finding

:warning: For commercial licensing of algorithm in rpoly, check rpoly.js or
http://www.netlib.org/toms/
http://www.acm.org/publications/policies/softwarecrnotice

:warning: rpoly.js is not wrapped in module for node.js.

Install
-------
    ~~npm install kld-polynomial~~

Polynomial
----------
- Polynomial.interpolate
- eval
- add
- multiply
- divide_scalar
- simplify
- bisection
- toString
- trapezoid
- simpson
- romberg
- getDegree
- getDerivative
- getRoots
- getRootsInInterval
- getLinearRoot
- getQuadraticRoots
- getCubicRoots
- getQuarticRoots

SqrtPolynomial
--------------
 - inherits from Polynomial
 - eval returns square root of Polynomial.prototype.eval
 