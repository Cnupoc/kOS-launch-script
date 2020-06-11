version 1.1 
====================================
reworked initial checks to flow faster and updated data displayed to staging.


version 1.2
===================================
- tweaked flight plan to be less aggressive and not so fast, tested both with light fast rockets and big wobbly heavy ones and it's satisfactory.
- reworked code structure to be less linear.
- the script is re-designed to work with LRBs and SRBs as initial stages with a main engine that overlaps 2 stages, but it works with normal rocket designs without boosters. Aspergous to be tested.
- there's a check for your last stage when eccentricity burn happens if you will have enough TWR to keep vert.speed. So very heavy and slow last stages are not welcome. 
