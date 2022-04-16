Simulation results
=============================
Some examples of outputs...

Cost Analysis
---------------------------
.. figure:: figures/Cost.png
   :scale: 100 %
   :alt: Logo

Betweenness Centrality
---------------------------
.. figure:: figures/NBC.png
   :scale: 100 %
   :alt: Logo


   >>> pressure.to_excel('pressure.xlsx')



Distance Calculation
---------------------------
.. doctest::   
   >>> r, pga, pgv, pos = Distance.com_pga_dist(node,ex,ey,M)
   
   
   
   
   
====================
Demo: Example Application
====================

.. _SeismoPi:
.. figure:: figures/network1.png
   :scale: 100 %
   :alt: SeismoPi


1.  Import SeismoPi dependencies, random seed and read nodes and pipes characteristics, and create model object.

.. literalinclude:: ../Examples/SeismoPi_ex1.py
    :lines: 1-20
    
    
2.  Define earthquakes

.. literalinclude:: ../Examples/SeismoPi_ex1.py
    :lines: 22-33
    
    
3.  Create Models and PGA estimates

.. literalinclude:: ../Examples/SeismoPi_ex1.py
    :lines: 35-102
    
