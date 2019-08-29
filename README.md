# mqtt-motion-sensor

Arduino PIR sensor to MQTT.

Expects an ESP8266 with a cheap PIR sensor connected to pin 14.  When motion is detected (the PIR sensor pulls the data pin high) it publishes a "1" to the MQTT topic `dinky/motion`, and when the PIR sensor pulls the data pin low again it publishes a "0" to the same topic.
