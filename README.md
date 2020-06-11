version 1.1 
====================================
reworked initial checks to flow faster and updated data displayed to staging.


version 1.2
===================================
- tweaked flight plan to be less aggressive and adjusted speed limitations at Ship:altitude and SHIP:apoapsis, tested both with light fast rockets and big wobbly heavy ones and it's satisfactory.
- reworked code structure to be less linear, but there's still on the to-do list for that. 
- the script is re-designed to work with LRBs and SRBs as initial stages with a main engine that overlaps 2 stages, but it works with normal rocket designs without boosters. Aspergous to be tested. Works with shuttles.  Basically if you have a thing that flies (or not) this script will launch it for you at desired apoapsis and perfect the orbit to 0.00~0.01 eccentricity.
- there's a check for the last stage when eccentricity burn happens if you will have enough TWR to keep vert.speed. So very heavy and slow last stages are not welcome. the program will end when the check is confirmed.
- rendezvous are WIP.
- i'm a newb. 
