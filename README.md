# alpha_wave_control_LED

Get the alpha wave control LED working on my OpenBCI v3.

Basically took chip's OpenBCI_8bits_HexBug here.
https://github.com/biomurph/OpenBCI_8bit_HexBug/tree/master/OpenBCI_8bit_HexBug

Get Processing for Hexbug here.
https://github.com/chipaudette/OpenBCI/tree/variant_hexBugControl_teamAlpha/Processing_GUI/OpenBCI_GUI

Check Library Hexbug.h and function issueCommand 

from 

digitalWrite(pins[command_pin_ind],LOW);  

change it to  

digitalWrite(pins[command_pin_ind],HIGH);

Then it will then trigger HIGH when alpha wave is being detected.
I am only using A1(GND) and A3(left command = channel 2)

https://www.facebook.com/yenkuang.chuang/videos/pcb.10209961321770097/10209961319130031/?type=3&theater ;
