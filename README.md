# IOT-ESP8266-Alexa_Skills_Garage_Door

Youtube tutorial https://www.youtube.com/playlist?list=PLYvhGlBkeltkMOW5gV37hKd2nmgLuuRt7

Alexa skills to control ESP8266 without opening a router's port/firewal.


In This project you will be able to control ESP8266 with Alexa skills without opening a firewall port or setuping a revers proxy.

1. Download this project and unzip.

2. Deploy this project to Heroku by clicking this button
    [![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy)

3. Copy following folders to "C:\Program Files (x86)\Arduino\libraries"

    arduinoWebSockets

    ArduinoJson

4. Update and flash your ESP8266 with "ESP8266/ESP8266_WebSocketClient/ESP8266_WebSocketClient.ino"

5. Create an Alexa skills and add Heroku app URL as an end-point

6. Test and enjoy.
