![alt text](https://github.com/emrelio/ANV_Flight_Computer/blob/main/ANV_V1.2/Medya%20Dosyalar%C4%B1/ANV1.jpg?raw=true)
<br />
<br />
Flight computer design for experimental model rocket flights.
<br />
<br />
<br />
I design this PCB for TVC of low power rockets.
<br />
<br />
<br />
Specs:
<br />
<br />
3-12V battery input,
<br />
Reverse battery protection,
<br />
3.3V and 5V switching regulators,
<br />
One main arm switch connector to cut all the power from the board,
<br />
Magnetic Switch connector for activation,
<br />
4, high current logic outputs,
<br />
All high current outputs have feedback for continuity detection,
<br />
4, 5v Servo outputs,
<br />
1,  LED and 1, active Buzzer connector,
<br />
1, RGB LED for notification,
<br />
ARM MCU,
<br />
Battery voltage and current sensors,
<br />
2, barometer from different brands for reliability,
<br />
9 DOF IMU,
<br />
4MB of memory for data logging,
<br />
Type-C connector for reading logged data,
<br />
433mHz LoRa for long-range wireless communication with U.FL connection,
<br />
Notification LED's for memory write and wireless communication,
<br />
Notification LED's for each high current outputs,
<br />
Screw terminal connector for power in-outs,
<br />
CAN-Bus connector for expansions in future,
<br />
M3 screw holes are connected to (BATT+, BATT-(GND), CAN-H, CAN-L).
<br />
<br />
<br />
<br />
<br />
Designed in KiCAD nightly.
<br />
<br />
Log:
Hall effect sensor out pin needs pull-up resistor, not pull-down. So It doesn't work.
3.3V regulator acting abnormally. I might overheated it while soldering. Will try it on another board.
Barometers and IMU is working.
USB VCP is working.
Current sensor is working.
Mosfet feedback is working.
Flash memory is working, but library is not fully compatible.
<br />
To-Do :
Lora
Can-Bus
Servo
<br />
<br />
