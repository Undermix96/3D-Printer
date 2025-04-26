# Calibration Steps

## Axis Twist Compensation
For X Axis Compensation run:
```
AXIS_TWIST_COMPENSATION_CALIBRATE
```

For Y Axis Compensation run:
```
AXIS_TWIST_COMPENSATION_CALIBRATE AXIS=Y
```

## Probe Z Offset
Home all axis, move head to center of the bed and run:
```
PROBE_CALIBRATE
```

#### Repeatability Check
Home all axis, move head to center of the bed and run:
```
PROBE_ACCURACY
```


## Perform Bed Leveling Operations (Optional)
Use probe-based bed leveling with [Screws Tilt Adjust](https://www.klipper3d.org/Manual_Level.html#adjusting-bed-leveling-screws-using-the-bed-probe)


## Bed Mesh
Do a Bed Mesh.

## First Time Calibration
### Resonance Compensation
[Link](https://www.klipper3d.org/Resonance_Compensation.html)

### Ellis' Print Tuning Guide
- [First Layer Squish](https://ellis3dp.com/Print-Tuning-Guide/articles/first_layer_squish.html)
- [Pressure Advance (Pattern Method)](https://ellis3dp.com/Print-Tuning-Guide/articles/pressure_linear_advance/pattern_method.html)
- [Retraction](https://ellis3dp.com/Print-Tuning-Guide/articles/retraction.html)
- [Infill/Perimeter Overlap](https://ellis3dp.com/Print-Tuning-Guide/articles/infill_perimeter_overlap.html)
