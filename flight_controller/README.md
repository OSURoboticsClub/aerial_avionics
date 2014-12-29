Aerial Flight Controller
========================
_Flight control board_

v4.0
----
_In progress_

Complete redesign with new microcontroller pin configuration. Significant
additions will include the following:

  * uBlox GPS
  * MS5611 barometer
  * MPU-9250 9DoF sensor in place of MPU-6000
  * MicroSD card reader
  * High-speed USB
  * More TIM channels and UART buses
  * Killswitch BJTs replaced with MOSFETs, and more of 'em
  * External SPI and I2C buses
  * Molex MicroLatch 2mm connectors in place of bulkier sherlock
  * Reverse voltage protection and TVS on 5V input
  * External crystal oscillator on STM32F4
  * Blinding status LED

This will be a development version with many debug pads and a rather open
layout for easier troubleshooting.

v3.4
----
2014 competition year. Separated IMU to daughter board to resolve board flex
issue. Added 2mm female headers to board for XBee.

v3.0
----
2013 competition year. Designed to work with and share form factor as Odroid
X2. Big issue with board flex affecting MEMS IMU.
