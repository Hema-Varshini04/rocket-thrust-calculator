# 🚀 Rocket Thrust Calculation Model

A web-based application for calculating and visualizing rocket thrust using important propulsion parameters.

## About the Project

The Rocket Thrust Calculation Model calculates the thrust produced by a rocket engine based on:

- Mass flow rate
- Exhaust velocity
- Exit pressure
- Ambient pressure
- Nozzle exit area

The application separately calculates momentum thrust and pressure thrust, then determines the total thrust.

## Features

- Calculates momentum thrust
- Calculates pressure thrust
- Calculates total thrust
- Displays step-by-step calculations
- Shows rocket thrust formulas
- Visualizes results using a bar chart
- Provides example input values
- Reset functionality
- Saves results using browser local storage
- Responsive web interface

## Formula Used

### Total Thrust

```text
F = ṁVe + (Pe − Pa)Ae
