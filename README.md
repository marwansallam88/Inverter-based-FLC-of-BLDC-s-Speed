Description:

This project dealt with the design of an FLC to control the speed of a BLDC. The simulation of the model was implemented on MATLab’s Simulink. The BLDC used was a four pole-pair three-phase BLDC as was commutated using six-sector commutation. The position of the rotor was measured as the integral of a motion sensor. The corresponding sector is output from a sensor block, which is in turn input to a commutation logic block. The commutation logic block determines the sequence of energizing the phases of the BLDC motor. The commutation logic outputs a PWM signal
based on a duty cycle as well as the switching pattern which is input to a three-phase inverter block connected to the BLDC. The duty cycle is determined by a FLC which takes as input the error between the desired speed and current speed as measured by the sensor block and outputs a duty cycle to the commutation logic block.

Key aspects:

•Simulated and implemented Fuzzy Logic Control (FLC) in MATLAB/Simulink to regulate motor speed with robust performance across a wide range.
