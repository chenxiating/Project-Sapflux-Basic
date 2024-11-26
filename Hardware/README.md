## Hardware

Multiple hardware variants of this design were created to leverage flexibility in the design process. Below is a description of the different variants.

#### [Alt - A](AltA/)

<!-- ![AltA Board](AltA/Sapflux-Basic_AltA-BOARD.pdf) -->
This board is a minor update of the design created by [Xiating Chen](https://github.com/chenxiating) and cleaned up by [Bobby Schulz](https://github.com/bschulz1701). 


#### [Alt - B](AltB/)

This board uses the same component set as [AltA](AltA/) but with an updated layout and some minor features added 

**Changes (vs AltA):**
- Addition of LED on output of heater line
- Updated board dimensions (kept constant for all other variants)
- Cutout and mounting holes for thermocouple amp
- Standard mounting of voltage regulator vs inverted mount on AltA

#### [Alt - C](AltC/)

This board adds support for all feature sets of onboard devices to allow for future firmware development to implement more advanced controls

**Changes (vs AltB):**
- Same mounting layout as AltB
- 9 pin header for thermocouple amp
	- All 4 alert lines from thermocouple amp are connected to feather
- Shutdown line on voltage regulator connected to feather

#### [Alt - D](AltD/)

This board adds all reasonable features while maintaining a simple hand soldered, through hole only design. Major addition here is the added support for soil moisture and rain gauge sensors

**Changes (vs AltC):**
- Same mounting layout as AltC
- Addition of 3 soil moisture sensor inputs 
	- Switchable power rail for soil moisture sensors with a MOSFET switch
	- LED placed on soil moisture power rail 
- Tipping bucket rain gauge connector added 