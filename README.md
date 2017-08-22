# my_ESP8266_mqtt_irrigator

Based on Instructables ESP8266 Smart Plant Irrigation System
https://www.instructables.com/id/ESP8266-Smart-Plant-Irrigation-System/

Before this project, register to EasyIoT Cloud service. 
We will need custom module type for irrigation system. 
Follow EasyIoT Cloud module configuration tutorial to add new ZMT_IRRIGATOR module type.
EasyIoT Cloud service : https://easyiot-cloud.com/
EasyIoT Cloud module configuration:https://iot-playground.com/blog/2-uncategorised/85-easyiot-cloud-module-configuration
Original Program codes:https://github.com/iot-playground/EasyIoT-Cloud/blob/master/ESP8266_mqtt_irrigator/ESP8266_mqtt_irrigator.ino

I have changed some I/O pins assignment. 
I used GPIO13(IO13) for PUMP_ON output and GPIO12(IO12) for ON/OFF switch input.

My EasyIoT Cloud source code examples.
For original EasyIoT Cloud source code examples and libraries, visit http://iot-playground.com/ for more information.


