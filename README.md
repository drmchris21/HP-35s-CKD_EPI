# HP-35s-CKD_EPI
CKD_EPI GFR

CKD_EPI formula is complicated because it contains 4 piecewise functions and 2 min/max functions none of them supported by the HP-35s calculator. In order to enter the sex as (male=1, female=2) and the race (Non African American=1, African American=2) I replaced the piecewise functions with the equivalent (Sex*x+y), (Race*x+y) finding the terms for x and y in every case solving some linear equations. Input parameters are A: Age, C: Serum Creatinine (mg/dL), S: Sex (1=male, 2=female) and R: Race (1=non african american, 2=african american). The program does not check the validity of the parameters.
