# Electronic Suite
Personal hub of electronics-related repositories, organized by category.<br/>
The work here grows from documented experiences: projects are built after the theory is experienced, libraries emerge from repeated practice.

These projects, when possible, follow a *Keep It Simple* approach, where simplicity means reducing degrees of freedom: building with what is available, standard-grade components included. The constraint is part of the design, requiring extra attention to detail to ensure that hardware limitations do not compromise final functionality.


---


<br/><img src="resources/banner-xp.svg" width="100%" alt="XP Banner">
A series of experiences exploring specific components, techniques, and design approaches. Each repository collects notes, circuit tests, and real-world measurements, and often serves as the foundation for my other projects.

>**[Hardware Notes](https://github.com/gom9000/hardware-notes)**<br/>
>**Type**: Hardware Design | **Status**: Ongoing
>
>A collection of practical notes about hardware calculations and development.

>**[Circuit Blocks eXPerience](https://github.com/gom9000/xp-circuit-blocks)**<br/>
>**Type**: Circuit Design | **Status**: Ongoing
>
>A series of experiences focused on testing, measuring, and dimensioning fundamental circuit building blocks.

>**[PSU Dummy Load eXPerience](https://github.com/gom9000/xp-dummyload)**<br/>
>**Type**: Dummy Load Design | **Status**: Ongoing
>
>A series of experiences on building different kinds of dummy loads to test small PSUs.

>**[SimpleBUS - A Simple BUS System eXPerience](https://github.com/gom9000/xp-simplebus)**<br/>
>**Type**: BUS Architecture | **Status**: Ongoing
>
>A home didactic experience focused on designing and implementing a simple 8-bit, I/O oriented BUS system. It includes the design of backplanes, activity monitors, and bridge boards to interface the system with CPUs like Raspberry Pi and PICmicro.

>**[PowerBank PSU eXPerience](https://github.com/gom9000/xp-powerbank)**<br/>
>**Type**: Power Supply Design | **Status**: Ongoing
>
>Design experiences for powering multiple 9V audio stomp boxes, exploring different power sources from external adapters to direct mains connection.

>**[RaspberryPI eXPerience](https://github.com/gom9000/xp-raspberry)**<br/>
>**Type**: Hardware Interfacing | **Status**: Ongoing
>
>A collection of experiments focused on interfacing the RaspberryPi with the external world.

>**[SwitchBank eXPerience](https://github.com/gom9000/xp-switchbank)**<br/>
>**Type**: Hardware Interfacing | **Status**: Concept
>
>A study on the classification and implementation of switch-bank circuits (arrays and matrices), focusing on momentary switches.

>**[Presepe Lights-Controller eXPerience](https://github.com/gom9000/xp-presepe-lights)**<br/>
>**Type**: Analog Design | **Status**: Ongoing
>
>A laboratory experience designing a modular controller for the lighting of a crib (nativity scene), with zero digital components, shifting state-machine logic and daily-phase timings entirely onto discrete BJTs, diodes, and operational amplifiers.

>**[PIC Assembly eXPerience](https://github.com/gom9000/xp-pic-assembly)**<br/>
>**Type**: Firmware Design | **Status**: Ongoing
>
> A technical diary of my learning journey with Assembly language for PIC microcontrollers (Mid-Range series). It covers base templates, timing routines (delays), I/O management with software debounce, and a cooperative scheduler designed for regular task execution. The experience also includes low-level MIDI protocol implementation (documented in the dedicated **[PIC Assembly MIDI eXPerience](https://github.com/gom9000/xp-pic-assembly-midi)** repository) with experiments on serial interfacing and bare-metal data transmission.


---


<br/><img src="resources/banner-lib.svg" width="100%" alt="Lib Banner">
Reusable assets (physical and digital formats) for electronics design.

>**[MOdule Boards Library (MOBs)](https://github.com/gom9000/mobs-library)**<br/>
>**Type**: Prototyping Library | **Status**: Ongoing
>
>A versatile collection of modular, single-function boards designed for rapid prototyping, component testing, and interfacing. Includes its own dedicated ExpressPCB library for board layouts.

>**[ExpressPCB Custom Library](https://github.com/gom9000/expresspcb-goslib)**<br/>
>**Type**: CAD Library | **Status**: Ongoing
>
>A collection of custom schematic symbols and PCB footprints designed for the ExpressPCB CAD software.

>**[LTspice Models Library](https://github.com/gom9000/ltspice-goslib)**<br/>
>**Type**: Simulation Library | **Status**: Ongoing
>
>A set of custom models and subcircuits for LTspice simulations, including power transistors, voltage level adapters, and functional blocks used to validate circuit designs.


---


<br/><img src="resources/banner-lab.svg" width="100%" alt="Lab Banner">
Custom-built instruments and tools designed to equip my workbench.

>**[Multi Out Low-Power Supply Unit](https://github.com/gom9000/mopsu)**<br/>
>**Type**: Power Supply | **Status**: Completed
>
>A versatile, multi-rail linear low-power supply unit (3.3V, 5V, 9V, 12V) designed to power bench prototypes.

>**[Diode Tester](https://github.com/gom9000/diode-tester)**<br/>
>**Type**: Component Tester | **Status**: Testing
>
>Measure the forward voltage drop ($V_f$) of diodes or the working voltage of Zener diodes under selectable currents (1mA, 2mA, 5mA, 10mA, 20mA, 30mA).

>**Dummy Load for Low-Power PSU *(coming soon)***<br/>
>**Type**: Active Load | **Status**: Development
>
>A 20W Constant Current (CC) load for PSU stress testing with adjustable current from 0A to 1A and input range from 1.5V to 30V.


---


<br/><img src="resources/banner-project.svg" width="100%" alt="Project Banner">
Electronics projects with a defined purpose and, sometimes, a concrete utility.

>**[Modular Presepe Lights](https://github.com/gom9000/modular-presepe-lights)**<br/>
>**Type**: Standalone Project | **Status**: Completed
>
>A set of simple modular, low-current, lighting controllers designed for the native scene display.

>**[UnoZero - Digital Logic Experiences](https://github.com/gom9000/unozero)**<br/>
>**Type**: Standalone Project | **Status**: Ongoing
>
>A modular educational hardware kit designed to build and explore digital logic systems without requiring deep discrete electronics knowledge. The system features a custom ecosystem of interconnected single-function boards (SF) - including clock generators, pulse sources, BCD displays, and counters - to perform hand-on laboratory experiments inspired by the classic Bugbook series.

>**[EEPROM 28C Programmer](https://github.com/gom9000/eeprom-28C-programmer)**<br/>
>**Type**: Hosted Project | **Status**: Completed
>
>A C-based programmer tool for 5V parallel EEPROMs of the 28C family hosted by a Raspberry Pi. The tool leverages bidirectional level translators to safely control and write data to the target non-volatile memories via terminal commands.

>**[Camera Remote Shutter](https://github.com/gom9000/camera-remote-shutter)**<br/>
>**Type**: Standalone Project | **Status**: Completed
>
>A hardware-based remote controller designed to trigger the focus and shutter stages of DSLR cameras, specifically tested on the Canon EOS400D. The system uses a PIC12F implementation written in Assembly (MPASM), interfacing with the camera via a standard 3-pin remote terminal.


---


## About
**Author**: Alessandro Fraschetti (gom9000).