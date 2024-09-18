NAME: Grace-lilie Acheampong
Date: 9/18/2024

This lab aims to help us understand how microcontrollers interact with the real world. We first studied the general structure of the micro controller and proceeded to run a code which blinks the red light and green light.

**RED LED BLINKING:** This project controls a RED LED on a microcontroller using a push button. Pressing BUTTON1(4.1) toggles the LED. A pin number output(1.0) was used as the output. when the button was pressed, the light will turn on and when it is pressed again the light goes off. Delays were added to read the signal after a set time to prevent transmission of fluactuating signals.

**GREEN LED BLINKING:** Similar to the red lED blinking, The green LED is controlled by pressing the BUTTON(2.3) on the microcontroller. A pin number output(6.6) was used as the output. when the button was pressed, the light will turn on and when it is pressed again the light goes off. Delays were added to read the signal after a set time to clearly outline the output.

In order to make the code more neat and organised, functions were introduced into the LED blinking code. The function was declared, defined and called to optimise the code. They were futher separated into header, source file and the main body. 
**GPIO HEADER FILE:**  In The header file, The functions were declared. 3 of the functions had a return type of void and one returned a character. 
**GPIO SOURCE FILE:**  In The source file, The functions were defined. A clear definition of the purpose of the functions were outlined. 
**GPIO main FILE:** The main file is where all the functions were called to be used by our microcontroller. With this our code is more clear and concise.
