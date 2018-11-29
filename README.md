# IOT
### Problem statement
In this busy world, people nowadays find it comfortable to control things from the place where they are using smartphones and PCs according to the purpose. Thus we came upon an automation idea of controlling home appliances from the web server. The home appliances include 240V bulbs. We can extend the same for other electronic devices also.

### Components required
* ESP8266
* Two 240V Bulbs with holders
* Resistors and led bulbs (for testing)
* Jumper wires
* Breadboard
* Arduino IDE
* Two 5V relays

### Description
The idea is to connect each of the electronic devices to different ports of ESP8266 and to connect the board to our local wifi network so that we can control these electronic devices through this local network.
We included the HTML script that contains respective on and off buttons for each device at each port in the ESP8266. 
We run a code in Arduino IDE connecting to the web server and once we receive the response by pressing any of the buttons the corresponding ports will be activated thus controls the devices from the web server using ESP8266. 
   
   
### Team Members

* D.L. Sarvani 		(AM.EN.U4CSE16121)
* Ch. Vennela		  (AM.EN.U4CSE16219)
* Gopika J		    (AM.EN.U4CSE16027)
* Nikitha N		    (AM.EN.U4CSE16245)

### Individual Contribution

* D L Sarvani - Taken care of the code to control bulbs at different ports and HTML for the webpage.
* Ch. Vennela - Taken care of the code to connect ESP8266 to Wifi and made ESP8266 as server.
* Gopika J - Did the hardware connections which includes connecting bulbs to ESP8266 module using relays.
* Nikitha N - Connected ESP8266 module to the code and tested the whole project with LEDS and rectified flaws.

### Individual Learning

* D L Sarvani - Learnt how to connect to different ports of ESP8266 and how to include HTML into ESP module.
* Ch. Vennela - Learnt how to use ESP8266 as client, implemented a echoserver. 
* Gopika J -  Learnt how to use ESP8266 as client and how to communicate between client and server.
* Nikitha N - Learnt how to use ESP8266 as server.
