# Getting started with Mindi® simulation and AVR®DB microcontrollers
This guide will get you up and running with simulating the analog OPAMP module in AVR DB family devices using the Mindi simulation tool.
## Configuration: voltage follower
Voltage follower is an opamp configuration in which the output voltage tracks the input voltage.  Also known as a unity gain amplifier.

![Voltage Follower](https://github.com/xedbg/Mindi_AVRDB_voltagefollower/blob/master/images/configuration.png)

### Mindi Simulation
<img src="images/mplab-mindi-analog-simulator.png" width="100"/>

Download and open the differential **Mindi schematic [here](https://github.com/xedbg/Mindi_AVRDB_voltagefollower/releases/latest/download/Differential_Amplifier.wxsch)**
Download and open the follower **Mindi schematic [here](https://github.com/xedbg/Mindi_AVRDB_voltagefollower/releases/latest/download/Voltage_Follower.wxsch)**

Press the _play_ button to simulate with an example stimulus source.

### Tweaking
A voltage follower has no adjustable resistor values.

### Updating composer fields
Once the desired result has been verified with Mindi simulation, the corrected values should be moved back into MCC/Start by copying resistor values across to the composer of your preference.

### Don't have Mindi?
Download and install [Mindi simulation tool](https://www.microchip.com/mplab/mplab-mindi)
Download and install Mindi model for AVR DB device
