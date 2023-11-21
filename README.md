# ESP8266 WIFI DEAUTHER

<img src='https://deauther.com/img/logo.png' alt='Deauther Logo' width='200' />

**Scan for available WiFi networks, selectively block certain connections, and generate multiple networks to obscure WiFi scanning.**

## Renewed Documentation

Hola 👋🏻

This repository contains code and documentation for performing WiFi deauther attacks using an ESP8266 microcontroller.

## Table of Contents
* [Buy](Buy)
* [About_this_Project](#About_this_Project)
* [Prerequisites](#prerequisites)
* [Usage](#usage)
* [Security Considerations](#security-considerations)
* [Connet_Wifi](#Connect_Wifi)
* [IP_Address](#ip_address)
* [Password](#Password)

## Buy
[Nodemcu_Esp8266](https://www.amazon.in/Generic-Nodemcu-Esp8266-Internet-Development/dp/B07262H53W/ref=mp_s_a_1_3?crid=IKVR7FGW4Z8O&keywords=esp8266&qid=1694963222&sprefix=esp8266%2Caps%2C523&sr=8-3)

## About_this_Project

This firmware allows you to easily perform a variety of actions to test 802.11 networks using an [ESP8266](https://www.espressif.com/en/products/socs/esp8266). It's also a great project for learning about WiFi, microcontrollers, Arduino, hacking and electronics/programming in general.

The deauthentication attack is the main feature, which can be used to disconnect devices from their WiFi network.  
Although this denial-of-service attack is nothing new, a lot of devices are still vulnerable to it. Luckily this is slowly changing with more WiFi 6 enabled devices being used. But a lot of outdated WiFi devices remain in place, for example in cheap IoT hardware.
With an ESP8266 Deauther, you can easily test this attack on your 2.4GHz WiFi network/devices and see whether it's successful or not. And if it is, you know you should upgrade your network.


## Prerequisites

Before you begin, make sure you have the following prerequisites:

- An ESP8266 microcontroller (e.g., NodeMCU, Wemos D1 Mini)
- Arduino IDE with ESP8266 support installed
- Knowledge of how to flash code to an ESP8266 device
- Basic understanding of WiFi and networking concepts  [Optional]

## Usage

1. Download this repository.
3. Open the [flash_download_tool_3.9.5.zip](https://github.com/cyber5kalki/wifi_deauthentication/files/12643043/flash_download_tool_3.9.5.zip) and load the provided code.
4. Configure the code with the target WiFi network information and the ESP8266 settings.
5. Upload the code of [esp8266_deauther_2.6.0_NODEMCU.zip](https://github.com/cyber5kalki/wifi_deauthentication/files/12643061/esp8266_deauther_2.6.0_NODEMCU.zip) to your ESP8266 device.
6. Run the code on the ESP8266 to initiate WiFi deauthentication attacks.

**Note:** Be aware of the legal and ethical considerations when performing WiFi deauthentication attacks. Ensure you have proper authorization to test or use such techniques on a network.

## Security Considerations

- Only use this code for legitimate and authorized purposes, such as network testing and security assessments.
- Respect the laws and regulations related to network security in your jurisdiction.
- Do not use this code for malicious or illegal activities.

## Connet_Wifi

- You need to connect the adapter to the plug, and it should display a blue blinking light on the board
- Connect the Showing wifi name: pwned password: deather

## IP_Address
- The module's IP address is 192.168.4.1

## Password
- The password for pwned is ''deauther''
