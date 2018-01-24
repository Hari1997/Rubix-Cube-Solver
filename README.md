# Rubix-Cube-Solver

Solves the cube in 5s.
Uses 6 Stepper Motors to spin the 6 faces of the cube.
Esp8266 Nodemcu module was used for controlling the stepper drivers.

The structure for the Cube solver was made from Form board.

CODE:

https://github.com/httplib2/httplib2 - Link for httplib2 library for python


https://github.com/muodov/kociemba - Link for kociemba library for python

Put httplib2 folder and the below files in the same directory.

First calibrate colors under the present lighting condition by running colordetect.py




Then burn the C file stepper_final_cube to esp8266 Nodemcu module
Change SSID and password the in program

Then run the script cube_solver.sh


Video Link:

https://www.youtube.com/watch?v=O-Tbm4wf4_U
