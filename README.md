# Field-Oriented-Control-FOC---FPGA

As an extension of the thesis project, the FOC function was not able to be implemented on hardware due to various reasons. Therefore the main branch of this repository continues to implement the FOC on hardware and publish it on GitHub.

The main controller, likely operating on an FPGA or STM32 microcontroller series, is combined with a three-phase two-level inverter driver, which is designed in Altium Designer and implemented on the PCB layout. As a result, the branch includes FPGA or MCU programming of the control system, and the hardware design is composed of schematic and PCB layout. 