# Electronic Suite
Personal index of electronics-related repositories, organized by category.<br/>
The work here grows from documented experiences: instruments are built after the theory is experienced, libraries emerge from repeated practice, projects are the result of both.<br/>
A repository may appear in more than one section when it belongs to more than one category.


## Lab — Instruments & Test Equipment
A set of custom-built instruments for the electronics workbench, covering power supply, component characterization, and load testing.

The suite is an ongoing project aimed at creating a comprehensive ecosystem of reliable, home-made tools for the electronics workbench. New instruments are developed starting from documented laboratory experiences to ensure maximum reliability and empirical validation.

### **[Multi Out Low-Power Supply Unit](https://github.com/gom9000/mopsu)**
**Type**: Power Supply | **Complexity**: Low | **Status**: Completed

A versatile, multi-rail linear low-power supply unit designed to power bench prototypes

- **Key Features**:
    - **Quad Output Rails**: Dedicated $3.3V$, $5V$, $9V$, and $12V$ regulated lines.
    - **Current Capacity**: Supports up to $500mA$ combined for $3.3V/5V$ rails and $250mA$ combined for $9V/12V$ rails.
    - **Linear Stability**: Uses standard $78xx$ series regulators and high-capacity filtering for low-ripple output.


### **[Diode Tester](https://github.com/gom9000/diode-tester)**
**Type**: Component Tester | **Complexity**: Low/Mid | **Status**: Testing

Measure the forward voltage drop ($V_f$) of diodes or the working voltage of Zener diodes under controlled conditions.

- **Key Features**:
    - **Selectable Constant Current**: Calibrated steps ($1mA, 2mA, 5mA, 10mA, 20mA, 30mA$) via rotary switch.
    - **High Voltage Range**: Supports supply voltages up to $30VDC$, allowing characterization of a wide range of Zener diodes.


### **Dummy Load for Low-Power PSU *(coming soon)***
**Type**: Active Load | **Complexity**: Mid | **Status**: In Development

A Constant Current (CC) load for PSU stress testing.

- **Key Features**:
    - **CC Mode**: Adjustable current from $0A$ to $1A$ via potentiometer.
    - **Thermal Safety**: Designed to handle up to $20W$ continuous dissipation.
    - **Wide Input Range**: Stable regulation from $1.5V$ up to $30V$.


## XP — Documented Experiences
A series of documented laboratory experiences exploring specific components, techniques, and design approaches. Each repository collects experiments with theoretical background and empirical results, and often serves as the foundation for lab instruments or standalone projects.


## Lib — Libraries & Reusable Assets
Reusable assets for electronics design: ExpressPCB custom component libraries, LTspice models, and modular single-function boards (MOBs) for prototyping.


## Projects — Standalone
Standalone electronics projects with a defined purpose.


## About
**Author**: Alessandro Fraschetti (gom9000).