SeismoPi Modelling Framework
============================
The framework of performing scenario-based seismic damage and renewal cost analysis using SeismoPi is shown in :numref:`flowchart` 
The steps for estimating probability of failure of pipelines, stochastic damage analysis, renewal cost estimation, and interactive mapping are described in subsequent sections.

Estimating Seismic Damage
-------------------------
.. _flowchart:
.. figure:: figures/SeismoPi_Framework.png
   :width: 500
   :alt: flowchart

   Framework of seismic damage and cost analysis in SeismoPi


Seismic Intensity Estimation
-------------------------
Scenario-based seismic risk evaluation requires the evaluation of seismic intensity at a site given an earthquake characteristics. The seismic intensity at a site is estimated by utilizing ground-motion prediction equations (aka attenuation laws) for which earthquake characteristics (e.g., magnitude, epicenter location, and depth) are required. GMPEs are often developed by analyzing ground-motion records of a particular earthquake and are typically applicable for specific geologic conditions. GMPEs are used to estimate seismic intensities at sites.

GMPE proposed by Kawashima et al. (1984) and Yu and Jin (2008) are used for estimating PGA and PGV intensities. Following GMPE computes PGA (:math:`PGA`) based on Earthquake Magnitude (:math:`M`) and distance from epicenter (:math:`R`) in km, as follows:

.. math::
    PGA = 403 10^{0.265M}*{(R+30)^1.218}


Fragility Analysis
-------------------------

Damage and Cost Analysis
-------------------------

Plotting Results on OpenStreetMap
-------------------------

Corrosion Modelling
-------------------------
A number of corrosion models exist in the literature that estimate the expected depth of corrosion pit over time. Among these models, the model proposed by Rajani et al. (2000) and that proposed Petersen and Melchers (2012) were developed based on field investigation of corrosion dataset of CI pipelines, and therefore, both are applicable for CI pipes. 

.. figure:: figures/Corrosion_Model.png
   :scale: 100 %
   :alt: Logo
