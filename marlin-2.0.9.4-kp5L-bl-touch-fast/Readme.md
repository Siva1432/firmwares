# NOTE: Use at your own risk
## before you flash the firmware, it is designed to use bl touch to replace z min endstop, so please make sure the BL touch ground and signal pins are connected to zmin endstop slot.

## NOTE: After flashing firmware if you get "media init failed", do the following:
  # turn of the printer
  # remove sd card
  # turn on the printer, calibrate screen, then everything should work normal
  # connect to pronterface and perform PID autotune for both extruder and bed (current values are set for my all metal extruder mod)
  # Calibrate Extruder E steps
