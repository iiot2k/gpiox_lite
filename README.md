# @iiot2k/gpiox_lite

[![platform](https://img.shields.io/badge/platform-Raspberry--Pi-ff69b4)](https://www.raspberrypi.com/)

Raspberry Pi gpio addon example 

<a href="https://www.buymeacoffee.com/iiot2ka" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/default-blue.png" height="41" width="174"></a><br>
If you like my work and find it helpful, please support me.

## Detail
This example shows the use of Raspberry Pi GPIO in node.js as an addon module.<br>
GPIO access is done using Linux gpio character device interface (V2) implemented in C++.

## Build and Execute
Copy all files to a folder on Raspberry Pi (e.g. /home/pi/gpiox_lite).<br>
Change to this folder:
```
cd  /home/pi/gpiox_lite
```
Build addon:
```
npm install
```
Execute example:
```
node ./
```
