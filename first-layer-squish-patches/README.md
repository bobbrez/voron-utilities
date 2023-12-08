# First Layer Squish Patches v1

A set of 16x of Andrew Ellis's [0.25mm First Layer Patch](https://github.com/AndrewEllis93/Print-Tuning-Guide/blob/main/test_prints/first_layer_patches/First_Layer_Patch-0.25mm.stl), each with a 0.01 mm offset from the previous to help automate some of the calibration suggested in [Ellis' Print Tuning Guide - First Layer Squish](https://ellis3dp.com/Print-Tuning-Guide/articles/first_layer_squish.html).

![gauge](images/grid.png)

## Key Points

- GCODE files due to slicer limitations
- 16 tiles per set
- Each tile has a 0.01 change in z offset from the previous
- Designed for a Voron v2.4 with 350mmx350mm bed and CNC Voron Tap
- Printing with 70c bed and 235c hotend (calibrated for Polymaker Pro PLA)

## GCODE

Ideally these would be delivered in a more flexible format but since the patches are all done as a single layer and there is not an easy way to inject gcode between each object, the files are created as GCODE.

## Patch Sets

| Patch | ID  | `Patch Set 01` Z Offset | `Patch Set 02` Z Offset | `Patch Set 03` Z Offset | `Patch Set 04` Z Offset |
| ----- | --- | ----------------------- | ----------------------- | ----------------------- | ----------------------- |
| A     | 1   | -0.00                   | -0.14                   | 0.00                    | 0.14                    |
| B     | 1   | -0.01                   | -0.15                   | 0.01                    | 0.15                    |
| A     | 1   | -0.02                   | -0.16                   | 0.02                    | 0.16                    |
| A     | 1   | -0.03                   | -0.17                   | 0.03                    | 0.17                    |
| A     | 1   | -0.04                   | -0.18                   | 0.04                    | 0.18                    |
| A     | 1   | -0.05                   | -0.19                   | 0.05                    | 0.19                    |
| A     | 1   | -0.06                   | -0.20                   | 0.06                    | 0.20                    |
| A     | 1   | -0.07                   | -0.21                   | 0.07                    | 0.21                    |
| A     | 1   | -0.08                   | -0.22                   | 0.08                    | 0.22                    |
| A     | 1   | -0.09                   | -0.23                   | 0.09                    | 0.23                    |
| A     | 1   | -0.10                   | -0.24                   | 0.10                    | 0.24                    |
| A     | 1   | -0.11                   | -0.25                   | 0.11                    | 0.25                    |
| A     | 1   | -0.12                   | -0.26                   | 0.12                    | 0.26                    |
| A     | 1   | -0.13                   | -0.27                   | 0.13                    | 0.27                    |
| A     | 1   | -0.14                   | -0.28                   | 0.14                    | 0.28                    |
| A     | 1   | -0.15                   | -0.29                   | 0.15                    | 0.29                    |
