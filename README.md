# Global-stabilization
This software is for implementing simulations of 'Global stabilization' that steers towards an unspecified fixed point in Boolean networks. It is actually close to a simulator to find attractors and an interpretor of JSON file including information about attractors that is generated by that simulator.

We developed it based on [BooleaSim](https://github.com/jehoons/BooleanSim) that is python 3 package for finding attractors in Boolean network and was developed by jehoons.

FVS and Stable motifs 

# Install
**1. BooleanSim**

```
cd BooleanSim 
python setup.py install
```

**2. FVS**

   Refetr to [FVS finder](https://github.com/needleworm/fvs)

**3. Stable motifs**

   Refetr to [StableMotifs](https://github.com/jgtz/StableMotifs)

# Implementation

* normal.py is for finding attractors with no mutations.

* r9_mutation.pyis for finding attractors with r9 mutation.

* r10_mutation.pyis for finding attractors with r10 mutation.

* FVS_application_to_r9.py is for finding attractors with fixed nodes that correspond to fvs and r9 mutation.

* FVS_application_to_r10.py is for finding attractors with fixed nodes that correspond to fvs and r10 mutation.

* CK_application_to_r9.py is for finding attractors with r9 mutation to get CK using brute-force search.

* CK_application_to_r10.py is for finding attractors with r10 mutation to get CK using brute-force search.

* analysisBasic.py is for interpreting a JSON file generated by r9_mutation.py, r10_mutation.py, FVS_application_to_r9.py, FVS_application_to_r10.py to get information about attractos.

* averageActivity.py is for interpreting a JSON file generated by r9_mutation.py, r10_mutation.py, FVS_application_to_r9.py,  FVS_application_to_r10.py to get information about average activitis of attractos.

* averageActivityBruteforce.py is for interpreting a JSON file generated by CK_application_to_r9.py and CK_application_to_r10.py to get information about average activitis of attractos.

