# 8-Bit SAR ADC Board

## Project Overview

This project focuses on designing an educational 8-bit Successive Approximation Register (SAR) Analog-to-Digital Converter (ADC) board using discrete logic ICs.

The goal is to reengineer an existing ADC board and improve it for educational purposes.

## Project Objectives

- Understand the working principle of an 8-bit SAR ADC.
- Analyze the existing ADC circuit.
- Add an external clock input (CLK_IN).
- Add an external analog voltage input.
- Provide test points for important signals.
- Design and manufacture a PCB.
- Test and verify the ADC functionality.
- Prepare technical documentation.

## Working Principle

The ADC converts an analog input voltage into an 8-bit digital output using the successive approximation method.

1. An analog voltage is applied to the ADC.
2. The SAR logic generates a digital trial value.
3. The DAC converts the trial value into an analog voltage.
4. The comparator compares the input voltage with the DAC voltage.
5. The SAR logic updates each bit based on the comparison.
6. After eight bit decisions, the final digital output is displayed using LEDs.

## Project Phases

1. Circuit analysis and understanding
2. Requirements analysis
3. Schematic design and modifications
4. Simulation and verification
5. PCB design
6. Manufacturing and assembly
7. Testing and validation
8. Documentation


## Project Status

In Progress – Circuit Analysis and Design
