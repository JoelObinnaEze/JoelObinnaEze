# Joel Obinna-Eze

### ECE @ UCalgary | embedded systems, FPGA/RTL, and data systems

I build across the hardware/software boundary: from byte-level protocols and digital design tooling to reliable data infrastructure.

[LinkedIn](https://www.linkedin.com/in/joel-obinna-eze-5a1a262a2) · [Repositories](https://github.com/JoelObinnaEze?tab=repositories)

## Featured projects

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
