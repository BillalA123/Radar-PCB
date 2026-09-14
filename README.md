# Handheld Radar System

2.4 GHz radar capable of measuring distance, velocity, and Synthetic Aperture Radar (SAR).

## PCB

<p align="center">
  <img src="Images/Screenshot%202026-09-13%20185550.png" width="80%" alt="Handheld Radar PCB">
</p>

## Schematic

<p align="center">
  <img src="Images/Job1%20(10)-1.png" width="100%" alt="Handheld Radar Schematic">
</p>

## Overview

Handheld 2.4 GHz radar system capable of measuring distance, velocity, and Synthetic Aperture Radar (SAR) imaging.

### Design Features

- Designed an RF transceiver where a VCO and PA drive a power splitter feeding the transmit antenna and mixer, while an LNA amplifies the receive antenna signal before downconversion.
- Optimized a 2x2 antenna array in ANSYS HFSS, designing the feed network for impedance and phase matching.
- Implemented a 4th-order 15 kHz active low-pass filter to enable digital analysis of the received radar signal.

## Inspiration

This project was inspired by the MIT Cantenna Radar project.
