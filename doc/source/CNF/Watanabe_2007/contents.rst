=============================================================
Watanabe et al. (2007): Spray flamelets in Laminar CouterFlow
=============================================================

**Title**

Characteristics of Flamelets in Spray Flames Formed in a Laminar Counterflow

**Authors**

Hiroaki Watanabe, Ryoichi Kurose, Seung-Min Hwang, Fumiteru Akamatsu

**Summary**

Characteristics of flamelets within two-phase combustion. 2D numerical simulation. Effects of strain rate, equivalence ratio, and droplet size are examined in terms of mixture fraction and scalar dissipation rate.

There appear differences in the trends of gaseous temperature and mass fractions of chemical species in the mixture fraction space between the spray flame and the gaseous diffusion flame. The spray flame jhas lower scalar dissipation rate and the coesistence of premixed and diffusion-limited flame.

(1) Computational domain

.. figure:: images/cf_domain.png
   :width: 30%
   :align: center


(2) Mean mixture fraction :math:`\overline{Z}`, gaseous temperature :math:`\overline{T}`, and scalar dissipation rate :math:`\overline{\chi}`

  
.. figure:: images/Z_temp.png
   :width: 40%
   :align: center

.. 

  - For the gas diffusion flame, :math:`\overline{Z}` decreases monotonously as the axial distance increases.

  - For the spray flame, :math:`\overline{Z}` has the peak value at the center of the high temperature region, where the stagnation plane is located. This is because :math:`Z` is produced by droplet evaporation.

  - :math:`\overline{T}` and :math:`\overline{\chi}` have the peak value at two points on both side with respect to the peak of :math:`\overline{Z}`.

  - The decrease in :math:`\overline{T}` between twh two peaks is due to the droplet group combustion behavior: `Cooling effect` and slow combustion due to lack of oxygen.

  - Source term of :math:`Z` (:math:`\overline{S_{Z}}`): the droplet evaporate mainly in the upstream region.


.. figure:: images/Z_temp2.png
   :width: 60%
   :align: center

..

  - The distributions of :math:`\overline{Z}`, :math:`\overline{T}`, :math:`\overline{\chi}` of the spray flame do not correspond with those of the gaseous diffusion flame.

  - The peak temperature is larger than that of gaseous diffusion flame: This is because :math:`\overline{\chi}` in the spray flame is much lower. Flame temperature generally rises as :math:`\chi` decreases.

  - :math:`\overline{Z}`, :math:`\overline{T}`, :math:`\overline{\chi}` of the spray flame are not unique in :math:`Z` space and cannot be uniquely related to :math:`\overline{Z}`

  - The differences between upstream region and downstream region exist for :math:`\overline{Z}`, :math:`\overline{T}`, :math:`\overline{\chi}` of the spray flame: This is caused by an imbalance between the production rate of :math:`Z` in the upstream region and its transport-diffusion rate in the downstream.


(3) Flame index result

  :math:`\text{FI} = \Delta {Y_{C_{10}H_{22}}} \cdot \Delta {Y_{O_{2}}}`

.. figure:: images/FI.png
   :width: 30%
   :align: center
..

  - Diffusion and premixed flame are found to coexist in the spray flame.

  - Negative FI region first appears: Diffusion flame occurs. Rapid evaporation region.

  - Positive and nefative FI region on the lower side of the rapid evaporation region: This indicates the presence of premixed and diffusion flames. The reason why gas temperature in the spray flame is larger than the gaseous diffusion flame is because of the existence of premixed flame region.



(4) Strain rate effect (See Fig. 6, 7, and 8)

  - The ignition occurs earlier and the high :math:`\overline{T}` region spreads wider for the lower strain rate case.

  - Larger strain rates suppress the evaporation of the droplets; it reduces the residence time in the high temperatures and increases teh number of droplets penetrating the flame.


(5) Effect of equivalence ratio (See Fig. 11, 12)

  - As :math:`\phi` increases, the fuel ignites earlier, and the high :math:`\overline{T}` region becomes wider.

  - The decrease in the peak temperature value for the higher :math:`\phi` is caused by the cooling effect associated with droplet group combustion.


