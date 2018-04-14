# mangOH red

This repository for the samples for experimenting with mangoh red board. See the board details [MangOH Red](https://mangoh.io/mangoh-red)

Repository of samples and codes for the Mango Red board

## Background

The MangOH red expands the WP modules from Sierra wireless (WP7XXX) has an armv7 processor and qualcomm modem with the usual IO pins - GPIO, ADC, SPI and I2C. 

It runs on a customized Linux framework - [Legato.io](http://legato.io/). It is so much stripped down version that you might find it bit uncovienient compared to usual Raspberry Pi, 96boards and the alikes. 

Fortunately, you could build golang applications on the Pi (or cross-compile for arm) and run on the MangOH board by transfering.

### Few Challenges

* Atleast I found, wifi doesn't work off the shelf !!

