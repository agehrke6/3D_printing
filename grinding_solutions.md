# Compiling suggestions to eliminate nozzle grinding on the v400

- tighten belts to the correct tension. What is the best way to do this?
- Switch to gyroid infill
- Lower infill flow (try 98 first, then 95 if needed)
- Turn combing off
- Z hop to 0.3 or 0.4 (some say 0.55)
- Disable jerk
- reduce extrusion flow by 10%
- Properly reduce the printing (idle) speed 
- Change current from 0.5A to 2.0A
- Use adjustable feet on the bottom of the machine to keep it level
- Turn off STEALTHCHOP in config file, make sure to set it to 0 on the extruder too. Though some people say turn current to 2.0A and then dont touch stealthchop
  (RUN_CURRENT= 2.0 and STEALTHCHOP THRESHOLD = 0, but make sure to leave extruder current alone at 0.9)
- Turn off acceleration and jerk in Cura (because Klipper controls it)
- use PrusaSlicer
- increase print temp (220)

