
clifford: Geometric Algebra for Python
=======================================


.. ipython::

    In [138]: from clifford.g3 import *  # import GA for 3D space
    
    In [138]: from numpy import e,pi
    
    In [138]: a = e1 + 2*e2 + 3*e3 # vector 
    
    In [138]: R = e**(pi/4*e12)    # rotor 
    
    In [138]: R*a*~R    # rotate the vector  

    
    
This module implements Geometric Algebras (a.k.a. Clifford algebras). Geometric Algebra (GA) is a universal algebra which subsumes complex algebra, quaternions, linear algebra and several other independent mathematical systems.  Scalars, vectors, and higher-grade entities can
be mixed freely and consistently in the form of mixed-grade multivectors. 


.. image:: _static/blades.png
   :width: 500 px
   :align: center

If you think Geometric Algebra looks interesting and want to learn more, check out the `cambridge groups page <http://geometry.mrao.cam.ac.uk/>`_,  and here are some great introductory textbooks!

Also feel free to get a formula collection at: http://ctz.dk/geometric-algebra/

* Geometric Algebra for Physicists, by Doran and Lasenby
* Geometric Algebra for Computer Science, by Dorst, Fontijne and Mann
* New Foundations for Classical Mechanics, by David Hestenes

Documentation
------------------
.. toctree::
    :maxdepth: 1
    
    Installation
    QuickStartG2
    TheAlgebraOfSpaceG3
    EulerAngles
    ConformalGeometricAlgebra
    SpaceTimeAlgebra
    InterfacingOtherMathSystems
    PredefinedGAs
    PerformanceCliffordTutorial
    Example 1 Interpolating Conformal Objects
    Example 2 Clustering Geometric Objects
    
API
------

    
.. toctree::
    :maxdepth: 1
    
    api

Tools
------

.. toctree::
    :maxdepth: 1
    
    tools

Links
--------

* Symbolic geometric alebra module for python:  https://github.com/brombo/galgebra

* Cambridge GA group:   http://www.mrao.cam.ac.uk/~clifford

* David Hestenes' (The man)  website:  http://geocalc.clas.asu.edu/

* GAOnline - Conformal Geometric Algebra visualiser: http://gaonline.azurewebsites.net/


    


   


