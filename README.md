# dichroic-filter-reflection-tests-overview
Measured the transmission and reflection coefficients of dichroic filters over the incidence angles of 10-75 degrees in 5 degree increments. This characterization is done using LED sources and well understood PMTs.

**Materials**
+ R7600-U200 PMTs (1x1 in)
+ 50/50 beam splitter (1x1x1 cm)
+ dichroic filters (dimensions?)
  + Knight
    + 500 nm longpass - square
  + Edmund
    + 500 nm shortpass - square (best results)
    + 500 nm longpass - circular
+ LEDs
  + 405 nm
  + 450 nm
  + 505 nm  
+ collimator
+ rotating platform
+ cardboard PMT covers
+ felt sheilding

**Specs**
+ PMTs operated at -800 V
+ LEDs operated at 2 V
+ oscilloscope
  + channels (all 3 same settings)
    + DC50
    + 450 mV/div
    + 270 mV offset
  + timebase
    + 20 ns/div
    + 2.5 GS/s
  + trigger
    + Auto 10 mV
    + Positive edge
 + source
  +  frequency: 1 kHz
  +  amplitude: 3.5 Vpp
  +  offset: 2.1 Vdc
  +  pulse width: 40 ns
  +  rise edge: 10 ns

**Setup**
+ Collimated LED sent at a 50/50 beam splitter
  + half goes to normalization PMT
  + half goes to dichroic filter
    + transmitted and reflected light detected by PMTs
 
**Notes**
+ Transmission and reflection PMTs are always angled up at 15 degrees (including when normalized) to avoid reflections off of the glass PMT face returning into the setup. 

