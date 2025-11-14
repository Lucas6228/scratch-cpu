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






OPT EXTRAS

{{CURRENTSECOND}}

{{CURRENTMINUTE}}

{{CURRENTHOUR}}

{{CURRENTDAY}}

{{CURRENTDAYOFWEEK}}
