# HomeAutomation 
The home automation systems consist of two elements:
* Beckhoff PLC - the execution element,
* HomeAssistant - the visualization.

This is the usual approach to deal with that kind of project. 

# Beckhoff PLC
Beckhoff PLC is a brain that handles all signals coming from or to home devices such as wall buttons, door contact sensors, fans, or lights. Once you push the button on the wall, PLC will be informed, and the corresponding light will be turned on. The project is stored in [repo](todo: link to repo).


# HomeAssistant
Thanks to [Home Assistant](https://www.home-assistant.io/), it is easy to make data storage and visualization using already prepared Beckhoff's integration. It uses Ethernet and ADS protocol to excange information with the PLC. Home Assistant configuration is available [here](todo: link to repo).
