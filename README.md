# Ethernet Switch Development Board

**4-Port Managed Switch with 2× SFP Fiber + 2× RJ45 – STM32H7 Host**

## Overview

This custom Ethernet switch board was designed as a development and firmware bring-up platform for a managed Layer 2 switch solution.

It combines high-performance fiber and copper connectivity with a powerful STM32H7 host microcontroller, allowing full control and monitoring of the switch fabric for testing, validation, and future product integration.

## Key Features

- **Switch IC**: Microchip LAN96459F (128-TQFP) – Managed L2 Ethernet switch
- **Host MCU**: STM32H743BIT6 (ARM Cortex-M7)
- **Ports**: 
  - 2× SFP slots for fiber optic transceivers
  - 2× RJ45 10/100BASE-TX copper ports
- Host interface: RMII (data) + SPI (register/configuration)
- External 125 MHz reference clock for SerDes
- Dedicated power rails: 1.15 V (core/analog) and 3.3 V (I/O & PHY)
- Multiple test points and debug connectors
- Compact form factor optimized for lab use and prototyping

## Project Goal

The board was created to serve as a reliable hardware platform for:
- Hardware validation of the LAN96459F switch
- Switch firmware development and integration
- Port configuration and performance testing
- Diagnostics and link monitoring
- Future embedded product prototyping

It provides engineers with full access to the managed switch features while using the STM32H7 as the main control and application processor.

---

**High-performance fiber + copper Ethernet switch development platform.**
