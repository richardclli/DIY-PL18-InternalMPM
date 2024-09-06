# DIY-PL18-InternalMPM
An internal MPM (Multi-Protocol Module) for Flysky PL18 Mod

This internal module works with the modified version of Flysky PL18 that flashes with EdgeTX:

https://github.com/EdgeTX/edgetx/wiki/PL18-Hardware-Mod-for-Complete-EdgeTX-Support

For MPM firmware download, please visit the official page:

https://github.com/pascallanger/DIY-Multiprotocol-TX-Module

## Installation Procedures:
1. Add an antenna to the PL18

![Antanna Installation](https://github.com/richardclli/DIY-PL18-InternalMPM/blob/main/images/Antenna.jpg)

2. Solder the power control wire to PI.00 pin

![Add Power Control](https://github.com/richardclli/DIY-PL18-InternalMPM/blob/main/images/IntModPower.jpg)

3. Install the PCB and insert the power control pin, you may need to use a sticky tape to ensure the MPM PCB is fixed to the PL18 PCB properly.

![Install PCB](https://github.com/richardclli/DIY-PL18-InternalMPM/blob/main/images/ModuleInstall.jpg)

Note:
The 100k pull up resistor for the power control pin is for testing purpose, it DO NOT NEED to be soldered as per the images shown.
