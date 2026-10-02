# Thrust-Vectored-Drone-Daedalus-
A single edf drone that directs airflow using vanes to control its movement. 
Built from the ground up alone, with some inspiration from Ikarus from Tesla 500.

Current Status:
Mechanical designs are fully built at the moment, electronics have been soldered.
Currently running a TBS Lucid H7 FC, an elrs receiver connected to the FC, and a generic 40A esc.
Edf is 50 mm in diameter. The inlet was made custom to allow for fitment with the battery hub above.
Using a 4s 1300 mah lipo to power the whole thing, have an external PDB that the battery is connected
and powers the ESC. Powers the FC as well. Electronics have been validated using a custom PWM tester I made using an ESP32.
Controls in ardupilot are still in testing phase, I have yet to make a test bench for the drone because it's about 12 inches long.
