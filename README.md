# Using-COAP-protocol-to-transmit-temprature-and-Humidity

• First Things First, Connect Esp8266 with DHT11. DHT11 has got 3 pins. Connect Vcc with the 3V pin.
Connect ground with the ground pin os Esp8266. Connect the third pin with one of the data pins of your
choice [D0-D7]

• Now with the help of Coap libraries startt coap Server.

• Using the DHT libraries get the data from the dht sensor. Note that you might also need the adafruit
sensor library along with it.

• Using the inbuilt wifi adapter connect the ESP8266 with a wifi having a internet connection.

• In the Google chrome with the help of coap plugin try to access the Ip addres of mote and hit discover.
