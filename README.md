# Automated Window Blinds Project

## Introduction
Brief project description and objectives.

## Materials
- NodeMCU ESP8266
- 3S Li-ion Battery Pack
- 12V Motor with Encoder
- TP4056 Charging Module

## Circuit Diagram
![Circuit Diagram](path/to/image.png)

## Steps
1. **Assemble Battery Pack**
   - Connect three 18650 cells in series.
   - Integrate the BMS.
2. **Connect Components**
   - Connect the motor to the NodeMCU.
   - Wire the TP4056 module for charging.

## Code
```cpp
#include <AccelStepper.h>
// Full code here
