# Mini_ADAS - Headlight Automation
Headlight automation control in Vehicles based on speed and ambient light....
Beginners in automotive embedded, CAN communication, and Restbus Simulation.

# Features
o Threshold-based headlight control
o Manual or random ambient light input
o CAN signal monitoring and message transmission
o CAPL-based logic implementation
o Perfect as a mini portfolio project for interviews

📁 Repository Structure
├── capl/
│   └── headlight_control.capl       # CAPL logic
├── config/
│   └── project.can / project.cfg    # CANoe configuration
├── database/
│   └── signals.dbc                  # CAN database
├── cache/
│   └── *.dc                         # Auto-generated CANoe cache files (optional)
└── README.md



# How to Run
* Open CANoe
* Load the provided .can / .cfg configuration file
* Add the CAPL script to the simulation setup
* Load the DBC file into CANdb++
* Start Measurement in CANoe
* Observe:
  ** Ambient Light signal changes
  ** Headlight Status output

# Requirements
-> CANoe Version: 12 or higher recommended
-> CAPL Browser installed
-> Basic understanding of CAN signals & CAPL scripting

