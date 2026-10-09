# Joel Obinna-Eze

### ECE @ UCalgary | embedded systems, FPGA/RTL, and data systems

I build across the hardware/software boundary: from byte-level protocols and digital design tooling to reliable data infrastructure.

[LinkedIn](https://www.linkedin.com/in/joel-obinna-eze-5a1a262a2) · [Repositories](https://github.com/JoelObinnaEze?tab=repositories)

## Featured projects

### [FPGA 2D Graphics Accelerator](https://github.com/JoelObinnaEze/fpga-2d-graphics-accelerator)

[![Autonomous Pong running on a Tang Nano 20K and RP2040](https://raw.githubusercontent.com/JoelObinnaEze/fpga-2d-graphics-accelerator/main/media/pong-hardware.jpg)](https://github.com/JoelObinnaEze/fpga-2d-graphics-accelerator)

`SystemVerilog` `FPGA` `SDRAM` `SPI` `RP2040` `DVI`

Hardware-validated 2D graphics accelerator on a Tang Nano 20K with an RP2040 host. It renders autonomous Pong into a double-buffered RGB565 SDRAM framebuffer and produces 640 × 480 DVI-compatible video. The design includes CRC-protected command transport, burst scanout, clock-domain crossing, timing closure at 162 MHz, and 22 self-checking RTL/C tests. [Watch the hardware demo.](https://github.com/JoelObinnaEze/fpga-2d-graphics-accelerator/blob/main/media/pong-demo.mp4)

### [Embedded Telemetry Link](https://github.com/JoelObinnaEze/embedded-telemetry-link)

`C11` `CMake` `CRC` `Streaming protocols`

Heap-free telemetry framing for UART-like links, with byte stuffing, CRC-16 validation, defensive parsing, and recovery after fragmented or corrupted input. The core is hardware-independent and tested through a warning-clean CI build.

### [RTL Impact Explorer](https://github.com/JoelObinnaEze/rtl-impact-explorer)

`Python` `SystemVerilog` `Verilator` `Static analysis`

Traces signal drivers and loads across elaborated SystemVerilog designs. It reconstructs cross-module dependencies from Verilator JSON and exports a self-contained, keyboard-accessible browser report with source navigation.

### [AESO Generation Data Pipeline](https://github.com/JoelObinnaEze/aeso-generation-pipeline)

`Python` `DuckDB` `SQL` `Data quality`

Turns AESO hourly generation archives into validated, queryable tables with deterministic quarantine, file-level provenance, schema-version tracking, and replay-safe ingestion. Verified against a full month containing 165,168 observations across 230 assets.

## How I think about systems

```text
Hardware / Sensors
        ↓
Embedded Firmware
        ↓
Control + Telemetry
        ↓
Engineering Data Systems
        ↓
Analysis + Visualization
```

I am most interested in work where electrical hardware, firmware, software, and data have to operate as one system.

## Working with

- **Embedded and digital:** C, C++, SystemVerilog, STM32, FreeRTOS, UART, SPI
- **Software and data:** Python, SQL, DuckDB, PostgreSQL
- **Engineering workflow:** Git, CMake, automated tests, CI, synthesis, timing analysis
