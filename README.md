# Solar Powered USB Charger

## Project Overview

This project presents a Proteus-based simulation of a solar-powered USB charger designed to provide a regulated 5 V DC output for charging USB-powered electronic devices.

The circuit uses an LM317 adjustable voltage regulator to regulate the input supply and provide a stable 5 V output.

## Objectives

- Design a regulated 5 V USB charging supply.
- Simulate the circuit using Proteus.
- Step down and regulate the input voltage to 5 V.
- Analyze the voltage regulation and output performance.
- Develop a simple and practical renewable-energy-based charging solution.

## Circuit Description

The main components used in the circuit are:

- 12 V input source
- 10MQ100N diode
- LM317 adjustable voltage regulator
- R1 = 240 Ω
- R2 = 720 Ω
- C1 = 0.1 µF
- C2 = 470 µF
- 5 V output

The input supply is applied to the LM317 regulator through the protection/input stage. The resistor network connected to the ADJ pin sets the regulator output voltage to approximately 5 V.

## Output

The simulated circuit provides:

**Input:** 12 V DC

**Output:** Approximately 5 V DC

The regulated 5 V output can be used as the supply for a USB charging interface.

## Software Used

- Proteus Design Suite

## How to Run the Simulation

1. Install Proteus Design Suite.
2. Download or clone this repository.
3. Open the Proteus project file.
4. Run the simulation.
5. Observe the regulated output voltage.
6. Verify that the output is approximately 5 V.

## Simulation Result

The circuit produces a regulated output of approximately 5 V from the 12 V input source.

The circuit diagram and simulation results are provided in the `Results` folder.

## Future Improvements

- Replace the 12 V source with an actual solar PV source.
- Add a rechargeable battery and battery charging circuit.
- Add USB-A/USB-C output protection.
- Add over-voltage and over-current protection.
- Improve charging efficiency using a switching regulator.
- Develop a complete portable solar charging system.

