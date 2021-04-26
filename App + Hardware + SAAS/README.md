
Home Assistant allows you to control all your devices without storing any of your data in the cloud. Its an home automation hub where different devices with different protocols communicate with each other. This means you can link all your devices in just one place and build cool automations based on the state of all your devices.

There are different ways to install Home Assistant. You can run it on your computer or use a Raspberry Pi to act as an exclusive home automation hub

We have attempted to connect multiple devices and sensors 

Here user can control everything anywhere to make sure that one is completely aware of any activity going around at one’s home.
The UI shown above is admin controlled.

## Encryption:
- We used the Let's Encrypt open source service to get the SSL/TLS encryption for our Homeassistant URL.
- We have also disabled the brute froce possiblity by banning the IP to access the URL if it exceedes the allowed number of attempts for login.

## Cloud MQTT Server:
- We used the free cloud hosting (Cloud MQTT) to publish and subscribe messages between attached devices, sensors and Homeassistant.

