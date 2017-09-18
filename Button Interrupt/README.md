# Button Interrupt
Last lab you were introduced to the idea of "Polling" where in you would constantly check the status of the P1IN register to see if something has changed. While your code may have worked, it ends up spending a ton of time just checking something that has not changed. What we can do instead is use another two registers available to us from the GPIO peripheral, P1IE and P1IES, to allow our processor to just chill out and wait until something happens to act upon it.

## Task
Your goal for this part of the lab is to replicate your button code from Lab 2, where the LED should change states only when the button is pressed. This can be extended to include behaviors such as only have the LED on when the button is depressed, or have the LED blink one color when pressed and another when it is let go. Another behavior extends from the second lab which is speed control based on the button presses. For example, have the rate of the LED cycle between a few different rates.

## Extra Work 
### Binary Counter/Shift Register
Either use a function generator, another processor, or a button to control your microcontroller as an 8-bit binary counter using 8 LEDs to indicate the current status of the counter.

### Multiple Buttons
Come up with a behavior of your own that incorporates needing to use two buttons or more.