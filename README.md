Cobra Power Regulator

The Cobra Power Regulator , regulates incoming power to 5 Volts and delivers it to the Power Rails of the Breadboard.
Most of the time I use the power from the computer to power the Microprocessors. But the USB port on the computer 
do not deliver much current. The Regulator will be able to convert 7 to 35 Volts DC. From a AC wall outlet Powersupply. 
The circuit will use a LM7805 and a LMS1585ACT -3.3/NOPB. The closer the Wall Adapter is to +5VDC the less work the 
+5 volt regulator will have to do. The dropout voltage on these regulator is 2 volts, therefore you need %5 + 2 = 7 volts 
for the LM7805 to work. I recommend a 7.5Volt adapter. The +5 and 3.3VDC will be selectable via Jumpers to either or 
both Breadboard Rails. The output will be 5 volts, delivered by a LM7805, which with a heat sink can deliver 1.5A. 
The 5volt and ground will be delivered to the Left Power Rails of the Bread board. The Right Rail will be selectable 
as a ground, at J8. Meaning the right Ground rail could be used for a third voltage if desired.
