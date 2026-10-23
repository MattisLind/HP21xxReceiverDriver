### HP 21xx IO bus driver and receiver

This project aims to create replacement for the 75121 driver since they are quite expensive nowadays. In addition to that there is a design for a receiver that is CMOS 3V compatible.

The driver and receiver has been tested on a bread board using through hole mounted components and this is a layout using surface mount parts where six receivers or drivers have been combined into one DIP 24 compatible space.

I recognised that  the pullups on the driver inputs where pulling to 5V through a 2k resistor. To be fully 3.3V compliant this should of course be 3.3V. Since there are no 3.3V regulator on the driver I added a 3.3V output on the receiver which can be connected to the driver input.
