# mission-converter

A simple Python script that re-centers a vehicle around a new home point.
Useful for taking text WP files centered at some arbitrary location and
centering them around new home position.

Original Waypoint Placement            |  Shifted Waypoints
:-------------------------:|:-------------------------:
![](https://raw.githubusercontent.com/deliastephens/mission-converter/master/wp_far.PNG)  | ![](https://raw.githubusercontent.com/deliastephens/mission-converter/master/wp_corrected.PNG)

## Use
`mission-converter` is meant to be used with the UAV Fault Injection script;
it requires a dronekit-python vehicle to be sent is an variable into
one of the functions.

The WP file should be a text file in this format:
