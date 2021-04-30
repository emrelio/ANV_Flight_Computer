Flight computer design for experimental model rocket flights.



I design this PCB for TVC of low power rockets.



Specs:


3-12V battery input,

Reverse battery protection,

3.3V and 5V switching regulators,

One main arm switch connector to cut all the power from the board,

Magnetic Switch connector for activation,

4, high current logic outputs,

All high current outputs have feedback for continuity detection,

4, 5v Servo outputs,

1,  LED and 1, active Buzzer connector,

1, RGB LED for notification,

ARM MCU,

Battery voltage and current sensors,

2, barometer from different brands for reliability,

9 DOF IMU,

4MB of memory for data logging,

Type-C connector for reading logged data,

433mHz LoRa for long-range wireless communication with U.FL connection,

Notification LED's for memory write and wireless communication,

Notification LED's for each high current outputs,

Screw terminal connector for power in-outs,

CAN-Bus connector for expansions in future,

M3 screw holes are connected to (BATT+, BATT-(GND), CAN-H, CAN-L).





Designed in KiCAD nightly.


Log:
Hall effect sensor out pin needs pull-up resistor, not pull-down. So It doesn't work.
3.3V regulator acting abnormally. I might overheated it while soldering. Will try it on another board.
Barometers and IMU is working.
USB VCP is working.

