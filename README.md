# Thrust-Vectored-Drone-Daedalus-
A single edf drone that directs airflow using vanes to control its movement. 
Built from the ground up alone, with some inspiration from Ikarus from Tesla 500.
Every part designed was made by me and fabricated by me. All of the electronics were also soldered by me and picked by me.
I am also doing all of the controls in ardu-pilot. This is a completely independent and solo project.

Current Status:
Mechanical designs are fully built at the moment, electronics have been soldered.
Currently running a TBS Lucid H7 FC, an elrs receiver connected to the FC, and a generic 40A esc.
Edf is 50 mm in diameter. The inlet was made custom to allow for fitment with the battery hub above.
Using a 4s 1300 mah lipo to power the whole thing, have an external PDB that the battery is connected
and powers the ESC. Powers the FC as well. Electronics have been validated using a custom PWM tester I made using an ESP32.
Controls in ardupilot are still in testing phase, I have yet to make a test bench for the drone because it's about 12 inches long.

STLs and Solidworks can be provided if asked for.

Design Revisions:
Had a previous project named Baby Ikarus that was a proto type for this. Had issues with battery placement and COM.
Made battery vertical this time and have FC on the center axis for the COM. Servos are now directly controlling the vanes instead of having linkages.
