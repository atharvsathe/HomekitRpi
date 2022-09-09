# Home Automation using Apple Homekit (Non-commercial use)
This repository implments Apple Homekit on off the shelf hardware which is integrated to Home app across all Apple devices.

## Motivation
The main goal of the project is to develop smart home facilities for exiting home aplliances. The proposed solution is cheap and comes with easy to install modules.

## Architecture
The project consists of a gateway (raspberry pi 3) connected to active internet that communicates with the apple app. Raspberry pi works as a bridge for various ESP8266 modules that are connected to local host on wifi and reside in switch boxes that actually drive the appliances. \n
Supported accesories are: \n

- Power outlet
- Toggle switch
- Simple bulb
- Brightness controlled bulb
- Fan

## Future Work
Install Alexa, Google and any other firware on the gateway and control the home appliances with any of the above services simultanieously.

