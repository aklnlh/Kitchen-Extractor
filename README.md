# Kitchen-Extractor
This project is to allow automation of my basic Kitchen Extractor Fan.  This code is run on a ESP2866 12F 4 relay board, running ESPHome.
This solution allows me to use the extractor as it is, but also allow remote control as required using Home Assistant. I'm intending on putting in a current sensor on the power cables that go to the Hob and the Oven so that I 
can automatically turn the fan on with them.  I'm also able to automate the light when the kitchen lights turn off and on.  The Humidity sensor will allow the unit to automatically turn on and off dependant on the humidity/steam.

Due to the lack of input pins, I'm using a voltage devider to allow selection of fan speed, and light control. 

