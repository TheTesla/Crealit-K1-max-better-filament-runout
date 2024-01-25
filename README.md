# Better filament runout handling

This config lets the 3d printer continue printing with the 550 mm extra filament remaining between the filament runout sensor and the extruder, after the filament runout sensor has been triggered.

Inserting new filament triggers the filament runout sensor, resuming the paused print job after purging 50 mm filament in the air.

Thanks to _TheRationalPi_ for providing the delayed pause code. [1]

The two files must be copied to the folder: ``/usr/data/printer_data/config/``

[1] https://klipper.discourse.group/t/feature-request-filament-runout-trigger-pause-after-700mm-extruded-distance-delay/5586/5


