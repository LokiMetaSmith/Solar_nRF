## Archived: 2026-10-31

* Repository contains firmware (FW), hardware (HW), and software (SW) components for a small solar-only, battery-free device.
* The device harvests energy using a single BPW34 cell, boosted and managing energy with the TI B5504.
* It sends BLE advertisements every few seconds in direct sunlight.
* It measures temperature using an external I2C digital chip connected to a Raytac nRF module.
* HW directory contains subdirectories: Components, SIMS, Solar_Array, Solar_nRF, production.
* FW directory contains subdirectories: peripheral_lbs, solarScanner.
* SW directory contains a tempDashboard.py script.
