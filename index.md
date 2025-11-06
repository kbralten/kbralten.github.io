---
layout: default
title: "Projects"
---

Software Projects
==========================

Virtual Camera
---------------

-   [onvif_simple](https://github.com/kbralten/onvif_simple): Allows a USB camera to emulate an ONVIF compliant camera.
-   [WinCamHTTP](https://github.com/kbralten/WinCamHTTP): A virtual camera driver for Windows 11 that turns any MJPEG source into a camera.

Measurement and Test Instrument Tools
-------------------------------------

-   [vxi_proxy](https://github.com/kbralten/vxi_proxy): Proxies SCPI, MODBUS, and USBTMC (and more) into VXI-11 compatible devices.
-   [vxi_dash](https://github.com/kbralten/vxi_dash): A monitoring and state-machine-based control system for VXI-11 devices (or any devices supported by vxi_proxy).

Image and 3D Model Manipulation
--------------------------------

-   [STL_PNG_Depth](https://github.com/kbralten/STL_PNG_Depth): Converts 3D STL files into grayscale depth maps (PNG) and vectorized SVGs for laser engraving, CNC, and fabrication workflows. Includes slicing, segmentation, and web-based conversion options. Try the [interactive web tool](https://kbralten.github.io/STL_PNG_Depth/) to upload STL files and preview or download depth maps and SVGs.
-   [spot_svg](https://github.com/kbralten/spot_svg): Extracts a limited color palette from images and generates SVGs with polygonal regions for each color, ideal for stencils or simplified vector art.

Simple Calculators and Games
----------------------------

-   [Calculators](https://github.com/kbralten/calculators): A collection of useful calculators for various tasks. Try them directly via the [web-based tools](https://kbralten.github.io/calculators/):
    - [Electroplating ASF calculator](https://kbralten.github.io/calculators/electroplating_asf.html)
    - [Lumber calculator](https://kbralten.github.io/calculators/lumber.html)

-   Static Games: A collection of browser-based games. Play them directly:
    - [Gridlock](https://static-games.onrender.com/gridlock.html): Navigate challenging grid-based puzzles.
    - [Math Drop](https://static-games.onrender.com/mathdrop.html): Solve equations in a fast-paced number game.


Serial Debugging
----------------

-   [ss_term](https://github.com/kbralten/ss_term): A minimal Python + Tkinter serial terminal emulator that supports selecting EOL modes (`CR`, `LF`, `CRLF`) and sending raw bytes (hex input). Useful for quick interactive serial sessions and debugging devices.

-   [serial_snoop](https://github.com/kbralten/serial_snoop): A Windows WPF application that proxies between an upstream virtual COM port and a downstream real COM port, logging timestamped bidirectional traffic (hex and ASCII). Intended for monitoring and debugging serial traffic when used with virtual port drivers such as `com0com`.

