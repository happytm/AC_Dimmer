AC_Dimmer
=========

Draft sketch UNTESTED

To-Do:
* Build a 555 test harness to verify code does what I expect.

Mark Chester <mark@chestersgarage.com>
  
Dims household lights and other resistive loads.
  
* CAUTION: Do not use on flourescent lights or inductive loads! Verify your device can handle dimming before using.
  
Fires up to four triacs a certain length of time after detecting the zero-crossing of the mains line AC voltage.  The fire delay time is set by a potentiometer for each triac.
