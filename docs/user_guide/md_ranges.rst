Ranges
=======

The Dexterous Hand Lite kinematics are optimized to be as close as possible (within engineering
constraints) to the kinematics of the human hand.

+---------------------+----------+----------+----------+----------+----------+
| Joint(s)            | Min deg  | Max deg  | Min rad  | Max rad  | Notes    |
+=====================+==========+==========+==========+==========+==========+
| FF1, MF1, RF1, LF1  | 0        | 90       | 0        | 1.571    | Coupled  |
+---------------------+----------+----------+----------+----------+          +
| FF2, MF2, RF2, LF2  | 0        | 90       | 0        | 1.571    |          |
+---------------------+----------+----------+----------+----------+----------+
| FF3, MF3, RF3, LF3  | -15      | 90       | -0.262   | 1.571    |          |
+---------------------+----------+----------+----------+----------+----------+
| FF4, MF4, RF4, LF4  | -20      | 20       | -0.349   | 0.349    |          |
+---------------------+----------+----------+----------+----------+----------+
| TH1                 | -15      | 90       | -0.262   | 1.571    |          |
+---------------------+----------+----------+----------+----------+----------+
| TH2                 | -40      | 40       | -0.698   | 0.698    |          |
+---------------------+----------+----------+----------+----------+----------+
| TH4                 | 0        | 70       | 0        | 1.222    |          |
+---------------------+----------+----------+----------+----------+----------+
| TH5                 | -60      | 60       | -1.047   | 1.047    |          |
+---------------------+----------+----------+----------+----------+----------+

The thumb has 4 degrees of freedom and 4 joints. Each finger has 3 degrees of freedom and 4
joints.
The distal joints of the fingers are coupled in a manner similar to a human finger, such that the
angle of the middle joint is always greater than or equal to the angle of the distal joint. This allows
the middle phalange to bend while the distal phalange is straight.
All joints except the finger distal joints are controllable to +/- 1° across the full range of movement.
