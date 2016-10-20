# MSP430 <3 DHT22

This is a test program / proof of concept of reading the [DHT22](http://www.lmgtfy.com/?q=DHT22) using Timer1A in the MSP430G2553 on the Launchpad and send data to UART communation (to ESP8266).

## Hardware

You'll need:
- MSP430 Launchpad with MSP430G2553 (or something else)
- DHT22 with required pullup resistor

Connect the data pin of the DHT22 to P2.0 on the Launchpad (that's pin 8 on J1).

Build, program, and see the temperature and humidity on your favorite serial console program.

Based on: https://github.com/rbasoalto/msp430-dht22



