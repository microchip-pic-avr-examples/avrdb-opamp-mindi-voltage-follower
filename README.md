# Getting started with Mindi® simulation and AVR®DB microcontrollers
This guide will get you up and running with simulating the analog OPAMP module in AVR DB family devices using the Mindi simulation tool.
## Configuration: voltage follower
Voltage follower is an opamp configuration in which the output voltage tracks the input voltage.  Also known as a unity gain amplifier.

![Volatge Follower](https://github.com/xedbg/Mindi_AVRDB_voltagefollower/blob/master/images/configuration.png)

### Simulation
Download and open the **Mindi schematic [here](https://github.com/xedbg/Mindi_AVRDB_voltagefollower/releases/download/0.0/VF2.wxsch)**

Press the _play_ button to simulate with an example stimulus source.

### Tweaking
A voltage follower has no adjustable resistor values.

### Updating composer fields
Once the desired result has been verified with Mindi simulation, the corrected values should be moved back into MCC/Start by copying resistor values across to the composer of your preference.

### Don't have Mindi?
Download and install [Mindi simulation tool](https://www.microchip.com/mplab/mplab-mindi)
Download and install Mindi model for AVR DB device
