# CSE2441-Term-Design-Project

This design project was to design a lock/display controller for a digital 
lock which displays “open” on a series of seven-segment boards if the 
code sequence "00-10-01" is entered, “deny” if any other code sequence
is entered, and “lock” if the digital lock is still in its locked state.

The design requirements specified the construction and use of a finite state
machine controller that satisfied the above input and output definitions, 
uses the minimum number of flip-flops and combinational logic elements, 
and does not produce any unwanted or undefined outputs.

The final implementation of this project was designed using the Quartus II
software, tested thoroughly using the QSim Simulation Software, and
implemented using the Altera DE-1 board.