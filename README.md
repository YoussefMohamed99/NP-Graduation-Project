# NP-Graduation-Project
In  this project we use 2 atmega32 microcontrollers to implement motor speed controller and printing the current speed on the LCD so we use UART to make the 2 microcontroller communicate to each other. The first one operate as UART sender it contains 2 push buttons one to increase speed and the other one to decrease the speed so when we click on it,it sends the speed to the second microcontroller which operate as UART receiver. It contains the LCD and the motor we control the speed of the motor using software PWM which we had implemented using Timers in CTC mode.   
