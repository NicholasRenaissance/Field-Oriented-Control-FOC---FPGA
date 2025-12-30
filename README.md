# Field-Oriented-Control-FOC---FPGA

As an extension of the thesis project, the Field-Oriented Control (FOC) function could not be implemented on hardware due to various constraints. Consequently, the main branch of this repository focuses on implementing the FOC algorithm on hardware and publishing the complete implementation on GitHub.

The main controller—expected to operate on either an FPGA or an STM32-series microcontroller—is integrated with a three-phase, two-level inverter driver. The inverter hardware is designed in Altium Designer and implemented through schematic capture and PCB layout. Accordingly, this branch encompasses both the FPGA or MCU programming for the control system and the complete hardware design, including schematics and PCB layouts.
