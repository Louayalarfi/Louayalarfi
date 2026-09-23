# Lauai Alerfi

New grad, B.Eng. Systems and Computing Engineering (University of Guelph, Ontario, 2026). I design digital hardware, RTL in Verilog and VHDL, FPGA and SoC integration, and full custom VLSI layout down to the transistor, and I build production software by directing AI coding agents while owning the tests and every decision about what ships. Currently a Software Developer at ECNG Energy.

Site: [lauaialerfi.com](https://lauaialerfi.com) | LinkedIn: [linkedin.com/in/lauaialerfi](https://linkedin.com/in/lauaialerfi)

Every repo below carries a topic matching its section, so you can also filter by `hardware-design`, `embedded-firmware`, `controls-and-dsp`, `software` or `mechanical-design`.

## Hardware design: silicon and FPGA

The core of what I do. Start with the SRAM macro.

- **[sky130-8x8-6t-sram-macro](https://github.com/Louayalarfi/sky130-8x8-6t-sram-macro)**, full custom 8x8 6T SRAM macro in the open source SkyWater Sky130 process, built from the bit cell up, DRC clean in Magic, bit exact addressed read and write verified in ngspice, with the engineering report.
- **[vlsi-program-counter-45nm](https://github.com/Louayalarfi/vlsi-program-counter-45nm)**, 8 bit program counter designed at the transistor level in a 45 nm CMOS process in Cadence Virtuoso: custom mirror adder, transmission gate mux and flip flop cells, functional tests and delay measurements at every level.
- **[aes-coprocessor-de1soc](https://github.com/Louayalarfi/aes-coprocessor-de1soc)**, AES 128 encryption coprocessor in the FPGA fabric of an Intel DE1 SoC, memory mapped over the Avalon bridge and driven from embedded Linux on the ARM HPS.
- **[fpga-vhdl-hls-zedboard](https://github.com/Louayalarfi/fpga-vhdl-hls-zedboard)**, VHDL on Xilinx Vivado and a Zynq ZedBoard, including a carry lookahead adder with a testbench and timing constraints, plus the same design again in high level synthesis.
- **[fpga-digital-design-labs](https://github.com/Louayalarfi/fpga-digital-design-labs)**, foundational Verilog on Quartus and the DE1 SoC: counters, seven segment displays, PLLs, an AES block.

## Embedded systems and firmware

- **[rtos-firmware-stm32](https://github.com/Louayalarfi/rtos-firmware-stm32)**, multitasking firmware on an STM32 ARM Cortex M target built twice on two kernels, FreeRTOS and uC/OS III: task scheduling, synchronization and a USB virtual COM port.
- **[arm-cortex-m-assembly-labs](https://github.com/Louayalarfi/arm-cortex-m-assembly-labs)**, Freescale K60 microcontroller labs in ARM assembly and C in Keil uVision.

## Controls and signal processing

- **[maglev-digital-control](https://github.com/Louayalarfi/maglev-digital-control)**, sampled data control of a magnetic levitation ball position plant, PI and LQR designs, MATLAB, Simulink and QUARC on real hardware.
- **[dsp-fir-filtering-matlab](https://github.com/Louayalarfi/dsp-fir-filtering-matlab)**, sampling, frequency analysis and FIR digital filter design in MATLAB.

## Software and simulation

- **[portfolio](https://github.com/Louayalarfi/portfolio)**, source for lauaialerfi.com, an interactive 3D portfolio in Three.js and Vite where every project is a device on a desk. Built by directing Claude Code agents through screenshot, lint and size gates, with a plain page kept as the fallback.
- **[glances-architecture-recovery](https://github.com/Louayalarfi/glances-architecture-recovery)**, architecture recovery and feature extension of the open source Glances system monitor: UML, analysis and new features.
- **[sugarscape-diet-simulation](https://github.com/Louayalarfi/sugarscape-diet-simulation)**, agent based Sugarscape simulation modelling macronutrient diets for weight loss, notebook plus report.

## Mechanical and team design

- **[capstone-pellet-3d-printer](https://github.com/Louayalarfi/capstone-pellet-3d-printer)**, capstone project, a compact pellet fed extrusion system for desktop FDM 3D printing.
- **[guide-assistive-system](https://github.com/Louayalarfi/guide-assistive-system)**, G.U.I.D.E, an assistive system for blind and low vision users, team design project.
- **[solidworks-rocket-wing](https://github.com/Louayalarfi/solidworks-rocket-wing)**, SolidWorks part modelling, assembly, drawings and animations.

All of the coursework repos come from the Systems and Computing Engineering program at the University of Guelph; the course each one belongs to is in its description.
