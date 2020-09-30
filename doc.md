On many operations-oriented model railroads, particularly those which use time-table and train-order (TT&TO) or tower-based dispatching, 
there is a need to provide telephone communications between the dispatcher and the agent/operators. However, even on large model railroads
with multiple agent/operators, the physical distances between the operator positions are often insufficient to allow the operators to
reliably determine that “hey that’s my phone ringing.”

The Morse Code Buzzer Controller serves up to seven stations, tapping out each ringing station's Telegraph call sign in Railroad Morse.
An additional output can be designated an “ambience” buzzer that will randomly play one of several canned messages. These could be train
orders, news reports, or “inside jokes”

The board accepts push button inputs, stops when the phone goes off-hook (phone must have a suitable contact to provide an isolated ground 
or use the MRCS Off-Hook_Detector) and can drive loads of up to 0.5 Amp at up to 48 Volts DC.  All buzzer/sounder devices must use the same
supply.  Sounders must have have a coil resistance of greater than 40 ohms if using a 12V supply, or else use our Sunder Driver.

This version accepts 10-24 VDC from the MRCS telephone bus or a layout auxilliary supply or an external wall wart (not supplied)

The on-board Arduino Pro-Mini runs the "station buzzers" sketch by Steve Williams.  Please indicate the telegraph codes for your 
stations, unless you intend to load the sketch yourself.
