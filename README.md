## DCI-P3 Color Space Enabler for OnePlus 3T
Note!!! Only for OnePlus 3T devices with a S6E3FA3 display panel. See below XDA link below for instructions on how to check.

This runs the following command in the "late_start" service:

`echo 1 > sys/devices/virtual/graphics/fb0/DCI_P3`

This was taken from https://forum.xda-developers.com/oneplus-3t/how-to/enable-dci-p3-op3t-s6e3fa5-display-panel-t3628783 so all credit to the awesome people who figured this out. All I did was package it as a Magisk module!
