# Inverter-based FLC of BLDC's Speed

## Description
This project implements a fuzzy logic controller (FLC) integrated with electronic inverters to control the speed of a brushless DC (BLDC) motor. The system uses a four pole-pair, three-phase BLDC motor with six-sector commutation, where Hall-effect sensors detect rotor position to determine the appropriate phase energization sequence. The FLC processes speed error signals to generate PWM duty cycle commands for the three-phase inverter, enabling precise and robust speed control across varying operating conditions.

## Key aspects
- Designed and simulated FLC-based speed control system in MATLAB/Simulink for a three-phase BLDC motor.
- Implemented six-sector electronic commutation using Hall-effect sensors for rotor position feedback.
- Integrated three-phase inverter with PWM control for precise phase voltage regulation.
- Achieved accurate speed tracking for both constant speeds (400-1200 RPM) and varying speed profiles.
- Demonstrated robust performance with satisfactory accuracy across different operating conditions.
- Utilized fuzzy logic with 7-input membership functions (error) and 7-output membership functions (duty cycle) for smooth control response.
