# ESP32-H2 Demo Zigbee Device

This project is a demo Zigbee device based on the ESP32-H2 / ESP32-C6. 

Modified to bypass the code for DHT22. See comments in c and h files to reverse changes.

## Features

- [x] DHT22 temperature and humidity sensor
- [x] Binary switch
- [x] Binary input

![Alt text](image.png)

## Hardware

- [ESP32-H2](https://www.espressif.com/en/products/socs/h2/overview)

## GPIO

| GPIO   | Function                                                                               |
| ------ | -------------------------------------------------------------------------------------- |
| GPIO8  | DHT22 data                                                                             |
| GPIO0  | Binary output (LED):  Catode til gnd, anode via 1k to GPIO0                            |
| GPIO12 | Binary input (Button): Button between GPIO12 and gnd. GPIO12 configured as internal pullup. |
