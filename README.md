# mobileUDAS
## mobile Underway Data Acquisition System

Data acquisition script for MLML mobile UDAS. Designed to run on a Raspberry Pi. Version 2 created by students in the MLML course MS 202 - Oceanographic Instrumentation (Jessica Meter, Marine Lebrec, Jason Gonsalves, Logan Grady).

### Instrumentation

- SBE 45 MicroTSG thermosalinograph (serial to USB connection)
- Wetlabs C-Star transmissometer (serial to USB connection)
- SUNA nitrate sensor (serial to USB connection)
- Turner C3 fluorometer (serial to USB connection)
- [Adafruit GPS breakout](https://www.adafruit.com/product/746) ([UART](https://learn.adafruit.com/adafruit-ultimate-gps/circuitpython-python-uart-usage) connection)

### Basic usage

- Open [UDAS_Master_Compilation.py](UDAS_Master_Compilation.py) and edit the COM ports, as necessary (see instructions in comments).
- Run the script [UDAS_Master_Compilation.py](UDAS_Master_Compilation.py).
- The [UDAS_FCNS_Module.py](UDAS_FCNS_Module.py) file contains functions for parsing data from each instrument. Additional functions can be added for other instruments if needed.
- See the user manual for full details on usage of the the UDAS system.
