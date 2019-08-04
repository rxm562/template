.. raw:: latex

    \clearpage

Roughness Model
===============

The roughness of pipelines increases with the increase in internal corrosion over time, which leads to a decrease in the roughness coefficient, C (Sharp and Walski 1988). Roughness coefficient depends on water quality, initial roughness, and pipe diameter (Sharp and Walski 1988)'[REF02]'.


.. doctest::

    >>> roughness (C)=18.0-37.2 Log R
    >>> R=(e_o+r_r*T)/D_i

where e_o=initial height of wall roughness (mm), which is zero for a new pipeline; r_r=growth rate in roughness height (mm/year); T= elapsed time since pipeline installation (year); Di=pipeline inner diameter (mm); R=time-dependent relative roughness.

Sharp and Walski 1988 Model
---------------------------
.. figure:: figures/Roughness_Model.png
   :scale: 100 %
   :alt: Logo


