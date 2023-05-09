Simple fire alarm using ADC and UART communication. 

Task is to read a temperature value from LM35 sensor (it is available on Proteus) via ADC pin and transmit this temp value in Celsius (°C) via UART to show on Virtual terminal. When temperatures value exceeds a certain threshold, a FIRE ALARM! message should be displayed on the terminal.  

The accuracy specifications of the LM35 are given with respect to a simple linear transfer function:  
VOUT = 10 mv/°C × T 
where  
VOUT is the LM35 output voltage 
T is the temperature in °C 
