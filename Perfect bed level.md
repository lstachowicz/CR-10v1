Perfect bed level can be achived by using paper test and printing. Paper test give you rought idea while printing give you real results. Some hints about printer calibration:

0. Install bed leveling system if you dont have.
If you use BL-touch unscrue top scrw and put layer between pin and screw. When screw magnetice it will keep pin from going down that can damage your build surface.

1. Level your bed 60 deg required on build surface
G28 # Homing
G29 # Bed level

2. Level your bed by using scrw. Even if you have bed level system you still need to level manually 60 deg required on build surface
You can reduce point to get rought idea how far you are.
G28 # Homing
G29 # Bed level

2. Calibrate probe by using paper test.
PROBE_CALIBRATE
TESTZ Z=<some value>
...
ACCEPT
SAVE_CONFIG


3. Calibrate probe by print multiple time until you get perfect print and good spaces between elements:
https://www.tinkercad.com/things/04VVCrpv1dh?sharecode=sy9gpOv_19MYxdoPmgd1eg406OxtN48Mx1qky8GftSg

PROBE_CALIBRATE
TESTZ Z=<some value>
...
ACCEPT
SAVE_CONFIG
