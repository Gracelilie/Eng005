# Lab Report: Microcontroller Interaction

**NAME:** Grace-lilie Acheampong  
**Date Written:** 9/16/2024  
**Date Updated:** 9/18/2024  

This lab aims to help us understand how microcontrollers interact with the real world. We first studied the general structure of the microcontroller and proceeded to run a code that blinks the red and green lights.

### RED LED BLINKING
This project controls a RED LED on a microcontroller using a push button. Pressing BUTTON1 (P4.1) toggles the LED, with output from pin P1.0. When the button is pressed, the light turns on; pressing it again turns it off. Delays were added to read the signal after a set time to prevent transmission of fluctuating signals.

### GREEN LED BLINKING
Similar to the red LED, the green LED is controlled by pressing BUTTON2 (P2.3) on the microcontroller, with output from pin P6.6. The light turns on with a button press and turns off when pressed again. Delays were incorporated to clearly define the output timing.

### Code Organization
To enhance code clarity and organization, functions were introduced into the LED blinking code. The functions were declared, defined, and called to optimize the code, and were further separated into header, source, and main files.

**GPIO HEADER FILE:** In the header file, the functions were declared. Three functions had a return type of void, and one returned a character.

**GPIO SOURCE FILE:** In the source file, the functions were defined with clear descriptions of their purposes.

**GPIO MAIN FILE:** The main file is where all the functions were called for use by our microcontroller, making the code more clear and concise.

### Dependencies
This project depends on the `msp430.h` library for accessing the MSP430 microcontroller's functionalities. For proper compilation and execution of the code, include this library

### Input and Output
**Inputs:**

BUTTON1 (P4.1): Press to toggle the RED LED.
BUTTON2 (P2.3): Press to toggle the GREEN LED.
**Outputs:**

RED LED (P1.0): Toggles on/off based on BUTTON1 press.
GREEN LED (P6.6): Toggle on/off with BUTTON2 pressed.
