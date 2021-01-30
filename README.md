# DIY-VAN-CONTROL

!!!FIRST STABLE RELEASE APRIL 2021!!!



Build a Raspberry-Pi/Node-Red Van Control System.


This system is based on Node-Red, so it can be used on different platforms. 
We're mainly talking about a Raspberry Pi  setup here. Since we're using the wifi of the RPI, model 3B or newer is recommended.
It has a modular flow system. Each flow provides seperate functions. 

Already done and working: 
- Nextion Display
- DS18b20
- Webasto W-Bus integration. 


Quick Start - Installing it yourself
1. Install NodeJS & Node-Red
2. Import the main flow
3. Setup your ports & your modules.
4. Import the flows
5. Toggle all flows you don´t use to inactive
6. Install the following extra nodes:
  - node-red-contrib-ads1x15
  - node-red-contrib-binary
  - node-red-contrib-ds18b20-sensor
  - ncd-red-comm 
  
  
  
  
Quick Start - Use our preconfigured image: 
- Burn our image to your SD card - (we recommend Win32 Disk Imager to do so)
- Put the SD card in your raspberry and you are ready to go
- Connect to wifi pekawayDIYcontrol (provided by RPI, model 3B or newer needed) - pw: pekawayYES
- Open the dashboard: http://peka.way
- Node-red config board - http://192.168.4.1:1880

Image: https://pekaway.de/pekaway_control.zip
- version 0.0.2



coming up: 
- china diesel heater protocol integration
- easy connect pcb, with waveshare 8 relais pcb
- raspberry pi hat pcb
- peacefair rs485 shunt
- daly/heyo BMS integration



All 3D-printed parts can be found here:
https://github.com/pekaway/3d-parts
