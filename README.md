# PLC_INOUT
Demo for Using Arduino PLC IDE with Arduino OPTA 8, for ModBus TCP protocol.

You can use all 8 input pins, the 4 output Relays Contacts and the various LEDs and have some registers
for counting and get the values from the Ladder Script for this Demo.

You can get the Information from the Arduino Opta via Modbus TCP on IPv4 192.168.1.232 on port 502.

The Modbus Address 255 is used to connect the OPTA as a Modbus Slave to a Modbus Master.

Currently, if you press the User Button, you will see the Blue LED turn on, the Output Relay O1 closed;
if you Press a button on Input pin 1 you will get the Red LED turned on.

Robert Gasperoni - 2023-05-09 09.30 
