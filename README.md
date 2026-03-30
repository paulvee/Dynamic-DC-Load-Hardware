# Dynamic-DC-Load-Hardware
Hardware information for the Dynamic DC Load

The Specifications:
- Input voltage: 1..100VDC.
- Reverse polarity protection to -100V and a 10A fuse.
- DUT is disconnected by a relays for invalid inputs like reverse polarity.
- Maximum current of 10A @ 40V
- Maximum power 180W @25 degrees ambient temperature (heatsink temp 85C)
- Off state DUT current 1.9uA at 2V, 57.7uA at 60V.
- Volt Accuracy: 0.4%
- Current Accuracy: 0.4% (using a two-point calibration for best precision)
- Native Calibration mode with commands entered over a serial connection
- Power input: 12VDC Wall-wart 0.5A with reverse polarity protection to -24V and PTC fuse
- CC, BT & CV modes with real-time operation regulated with hardware.
- In the BT mode, the operation is controlled by a seperate App that is tightly integrated.
- CP and CR modes have active regulation supported in software (resolution +/-156uA).
- Pulse/transient mode supported by an external Function Generator. 5V=10A
- Current monitoring with a DSO. 1V=10A
- GUI: 128x128 OLED 1.5' color display and a rotary encoder with dual button functions.
- Two temperature controlled fans.
- Protection for over voltage, over current, over power and over temperature limits
- Watchdog protection for stalled software and for the serial connection in the BT mode
- Overall dimensions: 21cm long, 18cm wide and a height of 118cm.
- Weight: approx. 1110 grams

The firmware for the Dynamic Load and the Batt Tester App are located in another repo
located here: https://github.com/paulvee/Dynamic-DC-Load

For details, visit my Blog : https://www.paulvdiyblogs.net/2024/09/building-diy-dynamic-dc-load.html
It gives you access to all information pertinent to the design and building of the Dynamic Load.


