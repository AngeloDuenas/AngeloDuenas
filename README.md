# Angelo Duenas

**Computer Engineering | Embedded Systems | PCB Design | Spacecraft Electronics**

I'm a Computer Engineering student at California State Polytechnic University, Pomona, pursuing my B.S. with an expected graduation in **May 2028**.

My work focuses on turning hardware concepts into practical embedded systems through schematic design, PCB layout, firmware development, and engineering verification. I'm especially interested in spacecraft electronics, low-power connected devices, and hardware miniaturization.

## Featured Projects

### CADENCE-SWANS | 12U CubeSat Payload Electronics

Contributing to the payload controller for **CADENCE-SWANS**, a 12U CubeSat project focused on space-weather and radiation monitoring.

- Developing and reviewing **KiCad schematics** for an **ATSAMV71-based payload controller**, including power distribution, current sensing, and peripheral interfaces.
- Defining electrical interfaces among the payload controller, **RadFET radiation-sensing boards**, and spacecraft flight computer, with attention to ADC measurements and command/telemetry paths.
- Evaluating power-system components, radiation susceptibility, system requirements, and verification procedures to prepare the hardware for integration and testing.

**Current stage:** Electrical design refinement, interface documentation, component review, and bring-up planning.

**Technologies:** KiCad, ATSAMV71, Embedded C, ADC, I2C, Power Electronics, System Integration

[View CADENCE repository](https://github.com/AngeloDuenas/CADENCE)

### GPS Tracker V2 | Miniaturized Cellular GNSS Tracker

Redesigning a GPS-tracking prototype into a **compact, rechargeable, low-power tracking device**, with the long-term goal of approaching a sticker-sized form factor.

- Exploring an **ESP32-S3** controller, **SIM7080G** cellular/GNSS connectivity, and **LIS3DH** motion sensing for event-driven tracking and low-power operation.
- Planning a custom PCB around battery capacity, charging, power regulation, antenna placement, component footprint, and sleep-state current consumption.
- Developed an early web-based tracking interface using **JavaScript, Leaflet, and OpenStreetMap**, with cloud location-data integration as part of the system architecture.

**Current stage:** Miniaturized PCB architecture, component selection, and power-budget evaluation; further integration and validation remain ahead.

**Technologies:** KiCad, ESP32-S3, LTE-M/NB-IoT, GNSS, Embedded Systems, JavaScript, Leaflet

[View GPS tracking interface prototype](https://github.com/AngeloDuenas/GPS-Tracker)

### Micromouse | Autonomous Maze-Solving Robot

Designed a custom **2-layer control PCB** for a Micromouse robot developed through **Cal Poly Pomona IEEE**, supporting autonomous navigation in maze-solving competition.

- Integrated an **STM32F411RE-based control platform**, infrared wall-detection circuitry, an IMU, dual motor-driver interfaces, wheel-encoder feedback, and regulated **3.3 V / 6 V** power.
- Developed **embedded C flood-fill path-planning logic** and simulated maze-navigation behavior.
- Refined component placement, decoupling, grounding, trace sizing, and mixed-signal routing; prepared the design for assembly, board bring-up, sensor checks, and closed-loop motor testing.

**Current stage:** Hardware integration and validation preparation.

**Technologies:** Altium Designer, STM32, Embedded C, PCB Layout, Infrared Sensing, Motor Control, Encoders

[View Micromouse repository](https://github.com/AngeloDuenas/Micromouse)

## Technical Skills

| Area | Tools and experience |
| --- | --- |
| **PCB and hardware design** | KiCad, Altium Designer, schematic capture, 2-layer PCB layout, component selection, mixed-signal routing |
| **Embedded systems** | C/C++, STM32, Microchip SAM microcontrollers, ESP32, UART, I2C, SPI, ADC, PWM |
| **Power and sensing** | DC-DC regulation, power distribution, current sensing, infrared sensors, IMUs, GNSS and cellular hardware architecture |
| **Engineering workflow** | Design reviews, interface documentation, datasheet analysis, integration planning, hardware test and debug |
| **Digital design** | Verilog, digital logic, FPGA fundamentals |
| **Development tools** | MPLAB X IDE, Git, GitHub |

## Current Focus

- Advancing the CADENCE-SWANS payload controller toward electrical verification and integration.
- Reducing GPS tracker size and power consumption through custom PCB design and component-level tradeoffs.
- Preparing Micromouse hardware for bring-up, sensor validation, and closed-loop motion-control testing.
- Building a stronger foundation in semiconductor design and hardware miniaturization.

## Connect

[LinkedIn](https://www.linkedin.com/in/angeloduenas/) | [GitHub](https://github.com/AngeloDuenas)
