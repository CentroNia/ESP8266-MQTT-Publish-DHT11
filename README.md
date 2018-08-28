# ESP8266-MQTT-Publish-DHT11
Publish the temperature and humidity information


1) Run the MQTT broker in a server (host : 10.10.10.10)

2) Subscribe the humidity/temperature topic in MQTT broker.

subscribe -t sensor/humidity

3) Upload the .ino file into ESP8266 board

4) Connect DHT11 signal pin to D6 pin which is GPIO12, Vcc to 5V and GND to GND of raspberry pi board.

5) Power ON the NodeMCU board.

6) You can see the temp and humidity data in raspberry pi terminal.

