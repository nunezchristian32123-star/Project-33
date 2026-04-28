# Project-33
Touch screen control
x and y cooridante variables first defined set to zero
readX function made to read x coordinate of touchscreen, with variable xr being the int value returned, pinmode for x coordinates -x and +x are set as INPUTS with a small delay before a value is read from it being xr which is later returned.
readY does the same but with y values.
Setup sets the serialbeing to allow for prints, and pinMode 6 as an output being the LED that is controlled.
In the loop readX is called and the returned value is assinged to x with the value being printed to the monitor, readY is also called to the same thing assinging y from readY and printing its value to the monitor. Variable int light is made and assing with a fouth of the yaxis value to allowfor control of the led. analogWrite then writes the LED on pin 6 with the y value assigned from the touchscreen.
