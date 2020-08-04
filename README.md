# Home_Automation

IMPLEMENTATION:
The system has two main modules: the hardware module and the software module. The hardware
module consists of two major components, ESP8266 Wi-Fi module and a relay module. The heart of
this system is the NodeMcu ESP8266. ESP8266 offers a self-contained Wi-Fi networking
arrangement; it can be utilized to host the application or to offload Wi-Fi networking capacities from
another application processor. Another important part of the hardware is the relay module. It is
used to regulate the switch to allow us to turn on or off circuit using the current which is much
higher than a microcontroller can handle. The relay protects the circuit from heavy voltage. Since we
are applying AC current to our circuit, it is very important for us to incorporate a relay module in
order to protect NodeMcu from heavy current.
The software Module consists of an Application which helps us to control the switch of the circuit
and make sure that the appliances are turned off and on using, the Wi-Fi itself. Apart from this, the
code is dumped in the NodeMcu, which makes the connection to be run wirelessly from one place to
where the circuit is put.


Requirements:
• NodeMCU
• Relay Module
• LDR Module
• Bread board
• Bulb
• Connecting wires

RESULT:
Therefore, our main objective has been fulfilled by idea of communication over internet
through Wi-Fi for controlling the microcontroller has been derived. Here the NodeMcu
ESP8266 has the capability to connect to the internet through Wi-Fi. By this we can control
the switch of the bulb and also we can make it automated accordingly by the help of LDR. By
the intensity of the surroundings the bulb is controlled.
CONCLUSION:
Thus, after performing this project we were able to reduce electrical expenditure in real life
lighting systems. The data sent from phone to the Nodemcu module using the ESP8266
module back and forth helped the user determine whether he wants the lights to be on or off.
This automation of lighting system has saved the user electrical expenditure which could not
have been done if this IoT based project was not successfully completed. Obstacles still exist
in the sense that the internet or the speed at which data packets are sent between the phone
and the server and then to the module is still slow for high range applications. The module
used is also fragile so a big enough impact can disconnect a vital connection which can result
in failure of the system, so care needs to be taken while installing this system in the domestic
housing structures when its made available for public use. In future, it can be implemented
with constrains and more advancement in the technology which can be operated more easily.
