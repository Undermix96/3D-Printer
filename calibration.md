# Calibration Steps

## Axis Twist Compensation
For X Axis Compesation run:
```
AXIS_TWIST_COMPENSATION_CALIBRATE
```

For Y Axis Compesation run:
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
