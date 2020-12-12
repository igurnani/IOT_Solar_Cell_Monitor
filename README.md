# IOT_Solar_Cell_Monitor
By Ishan Gurnani and James Yoo

Internet of Things device to detect buildup of dirt and debris on solar cells. During the day, real-time efficiency is calculated by comparing local solar radiation to power outputs, and at night, a photodiode sensor was used to measure reflectivity. Any dirty panel would have both reduced power output and irregular reflectivity.

Two methods were used since, for example, if efficiency is low but reflectivity is unchanged, it could be a mechanical problem, not an external buildup of dirt. Therefore, using the two in conjunction helps verify the output. 

If the panel is detected to be a dirty, an email is sent to the user using adafruit and IFTTT so that they can take appropriate measures to clean the panels. 
