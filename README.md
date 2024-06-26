# Dishwasher opener for ESPHome
Dishwasher opener . 
Since my dishwasher does not open automaticly when program is finished i made this to make sure that the drying is better when leaving my summerhouse.

Hardware:
- NodeMCU ESP8266
- Wiring
- Controller for the Linear actuator (https://www.aliexpress.com/item/1005006128416583.html)
- Linear actuator arm (https://www.aliexpress.com/item/1005003526985420.html)
- 12V powersupply

Configuration:
- Add to ESPHome and use via HomeAssistant

Connect the actuator arm to the controller, and connect the controllet to the ESP8266. If you remove the jumper in the middle of the controller you can power the ESP8266 from the same PSU (12V).

(https://github.com/solve-salvesen/dishwasheropener/blob/main/images/picture.jpg?raw=true)
