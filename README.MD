# Archived project - This functionality is now being continued in https://github.com/sjefferson99/pico-boat-assistant

Repositories in project:
Boatman project (this repo): https://github.com/sjefferson99/Boatman-project
Describes general project and components

Boat-server-uart: https://github.com/sjefferson99/Boatman-server-uart
Server code designed for pi zero execution to connect pico I2C hub to the boat network - may be replaced with webserver and signalk plugin repos

Boatman-webserver: https://github.com/sjefferson99/Boatman-webserver

Boatman-pico-wireless-hub: https://github.com/sjefferson99/Boatman-pico-wireless-hub
A wireless hub presenting a web server/API for control of the PICO Boatman devices connected via I2C

Boatman pico-uart-hub: https://github.com/sjefferson99/Boatman-pico-uart-hub
Display module with optional hub and I2C master if pico ESP not present - requires pi zero server over UART for network connectivity

Boatman-pico-lights: https://github.com/sjefferson99/Boatman-pico-lights
PWM LED strip controller to be used with LED driver circuitry for boat lighting control

Boatman-picodisplay-case: https://github.com/sjefferson99/Boatman-picodisplay-case
3D printed case for the Pico with display pack including exposure of IO pin repeaters

Overall architecture diagram:


![Architecture diagram](https://github.com/sjefferson99/Boatman-project/blob/master/Boatman%20network.drawio.png)
