Hint:

There are several jumper pads at the pcb.
These are bridges to enable/disable specific functionality, not SMD pads.

SJ1+SJ2: when bridged bypass the relay (no relay)
SJ3: when bridged disables the receive function (no-RXD)
SJ4: when bridged enables the transmit function

SJ4 is a bit tricky, as you must have it bridged in order to be able to transmit from the Raspberry PI to a telex machine, whereas all others disable functionality. 
The other tricky bit is that SJ4 is not shown in the PDF schematic diagram (https://github.com/fablab-wue/piTelex.supplement/blob/master/PCB/pyTelex.pdf)
