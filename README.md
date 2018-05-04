# SeeeduinoCloud Remote Monitoring
Environmental parameters such as temperature, humidity, noise,gas and light are sensed by SeeeduinoCloud, which is a microcontroller board based on Dragino WiFi IoT module HE and ATmega32u4. Then, those environmental data will be transmitted to Azure by IoTHub, which is a cloud service that offers reliable and secure device-to-cloud and cloud-to-device messaging that scales to millions of devices. 
# Hardware Requirement
SeeeduinoCloud: the more SeeeduinoClouds you have, the more places you can monitor.
Sensors: Temperature & Humidity Sensor, Light Sensor, Sound Sensor, Gas sensor and Chainable RGB LED.
Grove Base Shield V2: there are totally 16 grove connectors on the Base Shield.
# Build and Run
Download the code from Github, unzip the “Grove ChainableLED” and “Grove Temperature and Humidity Sensor” lib to libraries of Arduino IDE. Open seeeduino_remote_monitoring.ino with Arduino and Choose “Arduino Yun” in COM Port. Then click upload to download the app to the SeeeduinoCloud. Use Device Explorer to monitor the messages of the devices that is registered in the Azure IoTHub.
# More info
For more information, please refer to this project on hackster.io: cSense: Campus Environmental Surveillance System (https://www.hackster.io/JiongShi/csense-campus-environmental-surveillance-system-d12772).
