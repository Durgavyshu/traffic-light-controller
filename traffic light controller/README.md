# Traffic Light Controller using Verilog

## Overview

This project implements a simple Traffic Light Controller using Verilog HDL.

The controller is designed using a Finite State Machine (FSM). It controls
three traffic lights:

- RED
- YELLOW
- GREEN

The traffic lights change automatically according to the following sequence:

RED → GREEN → YELLOW → RED

## Features

- Designed using Verilog HDL
- Finite State Machine based design
- Synchronous state transitions
- Asynchronous reset
- Separate testbench
- Waveform generation using VCD

## State Diagram

RED
 ↓
GREEN
 ↓
YELLOW
 ↓
RED

## Files

```text
traffic-light-controller/
│
├── README.md
├── src/
│   └── traffic_light_controller.v
├── testbench/
│   └── traffic_light_controller_tb.v
└── simulation/
    └── simulation.vcds