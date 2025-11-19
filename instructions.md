# instructions

WTR: writes to ram.

example WTR 0022 0033 

That would write the number 33 to the 22nd ram thing.


RFR: reads a number from ram.

example RFR 3

That would read the third ram thing.


JMP: jumps to a line in the instructions

example JMP 8 

its obvious.


OPT: output to output list. Z for a number you read from ram.

example OPT 3354

output to output list:3354


CLR: clears the output list. can be used for gui i think. at this stage i havent added a input api.

DLY: delays the running in increments of 10 milliseconds

ISP: if space pressed. basically just JMP but only jumps if spacebar is being pressed at runtime

I1P: if 1 pressed. same as ISP but 1 instead of spacebar

I2P: if 2 pressed. same as ISP but 2 instead of spacebar

I3P: if 3 pressed. same as ISP but 3 instead of spacebar

I4P: if 4 pressed. same as ISP but 4 instead of spacebar

I5P: if 5 pressed. same as ISP but 5 instead of spacebar

I6P: if 6 pressed. same as ISP but 6 instead of spacebar

I7P: if 7 pressed. same as ISP but 7 instead of spacebar

I8P: if 8 pressed. same as ISP but 8 instead of spacebar

I9P: if 9 pressed. same as ISP but 9 instead of spacebar

I0P: if 0 pressed. same as ISP but 0 instead of spacebar



OPT EXTRAS


VVVVVVVVVVVVVVVVV


{{CURRENTSECOND}}

{{CURRENTMINUTE}}

{{CURRENTHOUR}}

{{CURRENTDAY}}

{{CURRENTDAYOFWEEK}}


^^^^^^^^^^^^^^^^^^^^
