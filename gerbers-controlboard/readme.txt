V1.04: Fixed the behaviour of locking keys during power-up and use.
To use this version of control board with the original keyboard which
I designed 2020, you need to remove D103, C7, R93 and R95 from under the
CapsLock key, then connect the button switch directly to the control line
(pin 2 on the SIP-40).  You may also omit all signal diodes from the
keyboard PCB, replacing them with 0-ohm resistors or jumpers. The new
keyboard revision has all of these fixes in place.

