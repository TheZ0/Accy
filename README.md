# Accy

![image0 (11)](https://github.com/TheZ0/Accy/assets/142558812/6843731b-1388-464a-9534-cef2d05106de)


Accelerometer module with on board memory to store data an support for micro-SD card to transfer data. Can also act as a USB to micro-SD card adapter.

## Specification
* 128kB of on-board flash memory allowing for storage of 7000 acceleration measurements for each axis
* Measurement range of +/- 16g for each axis
* Low power consumption of 0.25W
* Maximum transfer speed to micro-SD card of 19kB/s with SPI clock running at 4MHz

## Areas for Improvement
* Use SDIO interface instead of SPI to communicate with micro-SD card in order to increase transfer speeds
* Increase flash memory size to support higher sampling rates for a longer amount of time