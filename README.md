# EMG/EEG-Amplifier
3 Channel instrumentation amplifier circuit using AD8221. 

**EMG:** 1 channel, fully differential. 3.2 Hz highpass and 100x gain.   
**EEG:** 2 channels use a common reference. 1.1 Hz highpass and 100x gain.  

Gain is set using a single 499 Ohm resistor per channel. 
Input bandwidth is set by RC network.

Black wire: GND  
Red wire: +5V  
White wire: -5V  
Blue wires (3): Outputs  

.asc file can be opened with LTspice to run the circuit simulation and plot frequency response and transient analysis

 ![Alt text](/_1160748.JPG?raw=true "EMG/EEG Amplifier board")
