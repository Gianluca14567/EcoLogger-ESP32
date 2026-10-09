# EcoLogger-ESP32
EcoLogger ESP32 Board: documents

Here there are detailed schematics of the board and example of possible sensors connection.

Status:

The project is currently in the fully functional prototyping stage.
We have a robust, physical prototype completely populated and working in our laboratory.
All core hardware features, including the switching power supply, the triple-protected power rails, the bidirectional SDI-12 level shifter, both RS485 channels, the RS232 transceiver, the hardware-debounced rain gauge input, the 3 Open Collector outputs, and the 6-channel 16-bit external ADC over I2C, RTC, SD have been routed, assembled, and validated.

Main Components:

1) Espressif ESP32-WROOM-32: Dual-core 32-bit MCU running up to 240 MHz, featuring integrated Wi-Fi 802.11 b/g/n and Bluetooth v4.2 BR/EDR & BLE. Pre-certified (CE, FCC, IC, TELEC) to simplify compliance routing.

2) Six ADC inut Texas Instruments ADS1115 with jumper for insert 150 Ohm 1% resistor for 4-20ma sensors

3) Two Serial Transceivers RS485 A xor B

4) One Serial uart Texas Instruments MAX3232

5) Real time clock DS3231MZ with 3V li battery

6) SD removable card

7) SDI-12 port

8) Rain gauge 10Hz HW filtered port 

9) 3 open collector out 0.5A 12VDC

10) Mikroe bus espansion (except uart signals)

11) Internal ADC for ma current monitoring 

12) Internal ADC for input VDC monitoring

13) Internal Oled 128x64 dot for indication and debug

14) One internal push button

15) 3V3 / 12V /9V / 5V PTC protected power outs

16) Power input 10VDC to 15VDC polarity protection

