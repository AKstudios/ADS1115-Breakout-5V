# ADS1115 Breakout 5V
This is a modified version of the ADS1115 breakout board by Adafruit. It takes analog inputs between 0-5V, but the I2C interface is at 3.3V with the addition of logic level shifting circuitry to interface with 3.3V MCUs. All passive components are 0402 parts to fit everything on the board.

The board takes in raw power (2-16V) through the PWR pin and supplies a steady 5V to all components (MCP1703 LDO Vreg). The board has an input header for 3.3V supply for the level shifting circuit.

ALRT pin is not broken out, but still pulled up to 5V on the board.

<p align="center">
  <img src="https://github.com/AKstudios/ADS1115-Breakout-5V/blob/master/render.png" alt="CRT Sensor Board"/>
</p>
