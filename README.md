# Temperature_monitoring_using_IOT
Sending an Email when Temperature Crosses Threshold

Here I had written a program which would fetch the temperature data collected by Bolt(IOT device) and send an email if the temperature value exceeds the defined temperature range.

Hardware required
> The Bolt Wifi module

> 3 female to male wire

> Temperature Sensor: LM35 sensor

In the Images folder we can see the connections, VCC is connected to the red wire, Output is connected to the orange wire and Gnd is connected to the brown wire. Using male to female wire connect the 3 pins of the LM35 to the Bolt Wifi Module as follows:

> VCC pin of the LM35 connects to 5v of the Bolt Wifi module.

> Output pin of the LM35 connects to A0 (Analog input pin) of the Bolt Wifi module.

> Gnd pin of the LM35 connects to the Gnd.

When all the above connections are made we next need to create a email_conf.py which includes all the details about the BOLT device and 3rd party application that is MAILGUN for sending the alert messages if the threshold temperature which has been set here to (300,600) the values within the bounds are the values that are good for the operating conditions.

If the temperature decreases or increases out of the bound will be sent as an alert mail to the owner

So that it helps the owner to optimize the situation by taking proper care with no time 
