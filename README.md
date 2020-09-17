![Microchip logo](images/microchip.png)
# Getting started with Mindi™ simulation and AVR®DB microcontrollers
This guide will get you up and running with simulating the analog OPAMP module in AVR DB family devices using the Mindi simulation tool. For a larger overview, see ["Getting Started with Analog Signal Conditioning (OPAMP)"](https://github.com/search?q=topic%3Aavr-db+topic%3Agetting-started-with-opamp+org%3Amicrochip-pic-avr-examples).
## Configuration: voltage follower
Voltage follower is an op amp configuration in which the output voltage tracks the input voltage.  Also known as a unity gain amplifier.

![Voltage Follower](images/configuration.png)

### Mindi Simulation
![Mindi](images/mplab-mindi-analog-simulator.png)

Download and open the **Mindi schematic [here](https://github.com/microchip-pic-avr-examples/avrdb-opamp-mindi-voltage-follower/releases/latest)**


Press the _play_ button to simulate with an example stimulus source.

### Tweaking
A voltage follower has no adjustable resistor values.

### Don't have Mindi?
You can download and install the [Mindi simulation tool](https://www.microchip.com/mplab/mplab-mindi), or use another SPICE simulator of your own preference. For use with different simulators, a plain spice model can be found in "Opamp_AVR_DB.txt" to replace the mindi-optimized ".lb" 
