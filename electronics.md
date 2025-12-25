---
layout: default
title: "Electronics related"
---

Electronics related
====================

Measurement and Test Instrument Tools
------------------------------------

-   [vxi_proxy](https://github.com/kbralten/vxi_proxy): Proxies SCPI, MODBUS, and USBTMC (and more) into VXI-11 compatible devices.
-   [vxi_dash](https://github.com/kbralten/vxi_dash): A monitoring and state-machine-based control system for VXI-11 devices (or any devices supported by `vxi_proxy`).
-   [umdt](https://github.com/kbralten/umdt): Universal Modbus Diagnostic Tool — a Python toolkit for diagnosing, simulating, and bridging Modbus RTU/TCP devices. Includes an interactive CLI/GUI for reading/writing registers and probing networks, a configurable mock server with fault injection, and a soft-gateway bridge with PCAP logging. Ships with Wireshark Lua dissectors for easy packet analysis. (AGPL-3.0)

Other electronics instrument tools
----------------------

-   [fy3200s](https://github.com/kbralten/fy3200s): A small Python `PySide6` GUI and protocol wrapper to control the FY3200S two-channel function generator over a serial ASCII protocol. Features channel configuration, triggers, sweeps, measurement polling, and an arbitrary waveform editor. Includes a description of the FY3200S protocol.

Hardware interface
----------------------

-   [tf-luna](https://github.com/kbralten/tf-luna): Arduino sketches and example code for interfacing the TF-Luna LiDAR sensor (I2C and UART). Includes `TFLuna_I2C.ino` and instructions for wiring and testing distance measurements with an Arduino. (MIT License)

Protocol references
-------------------

-   [device_protocols](https://github.com/kbralten/device_protocols): Curated notes on command sets, pinouts, and interface quirks for various electronic test instruments (oscilloscopes, multimeters, signal generators, supplies, etc.). Browse the rendered reference at [kbralten.github.io/device_protocols](https://kbralten.github.io/device_protocols/). (MIT License)

PCB & Gerber Tools
------------------

-   [gerber_to_svg](https://github.com/kbralten/gerber_to_svg): Convert Gerber PCB files into clean SVG vector paths (and optional PNG exports). Supports drill file inclusion, polarity-aware rendering, and contour tracing (uses `pygerber` + `OpenCV`). Useful for vector output for CNC or laser engraving or previewing PCB copper/outlines for documentation. (AGPL-3.0)
-   [gerber_to_gcode](https://github.com/kbralten/gerber_to_gcode): Excellon (drill) → G-code converter for CNC. Parses Excellon drill files, supports metric/imperial and zero suppression modes, and chooses drilling vs spiral milling strategies depending on hole size. Optional arc/helical interpolation (`--use-arcs`) produces much smaller G-code and the script is configurable for bit size, depth, feed rates, and safe heights. Ideal for turning PCB drill files into safe, ready-to-run CNC G-code. (AGPL-3.0)
-   [gerber_cnc_gui](https://github.com/kbralten/gerber_cnc_gui): GUI for automating calls to `gerber_to_svg` and `gerber_to_gcode`. Given a top, bottom, outline, and drill file it creates two SVGs for top and bottom and a gcode file for routing and drilling.

KiCad
---------------------
-   [kicad_excel](https://github.com/kbralten/kicad_excel): The KiCad Excel Bridge is a .NET 9 WPF application designed to facilitate the integration of KiCad with Excel/CSV files. It provides a tray application with an HTTP API for managing and mapping fields between KiCad and Excel/CSV data. The application includes a user-friendly field-mapping UI and supports per-sheet settings for flexible configuration.

FPGA
---------------------
-   [The Pynq Learning Journey](https://kbralten.github.io/pynq_to_zynq/) and [Loopback Project](https://kbralten.github.io/pynq_to_zynq/loopback/): This project documents the complete path from using the PYNQ-Z2 board within the friendly, Python-based PYNQ ecosystem, to mastering it as a generic Zynq-7000 development board. It features the Loopback Project, a multi-step tutorial where to build a single, cohesive system that touches every layer of the embedded stack.