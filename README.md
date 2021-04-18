![](https://github.com/PanduKonala/PanduKonala/blob/main/header_.png)
<br>
# [Smart Safety System For LPG Containers](https://pandukonala.github.io/blog-work/lpg_iot/lpg_iot.html)
## Overview
> This project is funded by Amrita Vishwa Vidyapeetham. The Objective of the project is to design and develop a Cyber-Physical System for the safe transport system of Liquid Petroleum Gas (LPG) using ultra-sonic, MQ9 & DHT11 sensors which are linked to the cloud.

## Abstract

> Even the slightest rise in temperature should be seen with caution since if ever the temperature were to rise above the flashpoint of the gas or the liquid. So transporting such liquids/gases should be done with great caution. Even if all the necessary measures are taken to avoid the possibility of an explosion, there is still an element of risk to the person transporting the substance as well as to its surroundings. With the recent advancements in the field of the Internet of Things and electronics, we have access to sensors that can detect gases like LPG, CO, CH4, the slightest variations in temperature etc. So with the help of these sensors coupled with efficient algorithms, we will be able to detect whether the liquid has reached a point where it is no longer safe to transport it. So our project aims to develop an IoT system that can determine the safety level beyond which it is no longer safe to transport the liquid. In such a situation the concerned authorities are notified by our system and suppression measures will turn on.
<br>
To make a working model of our project, we have used a DHT11 sensor, an MQ9 sensor, an ultrasonic sensor, an Arduino UNO board and a NodeMCU. This is as far as the hardware is concerned. Regarding the software that was used, we used Arduino IDE, Adafruit Cloud, IFTTT app.

## Hardware Components
> • DHT11: It is a temperature sensor. It is used to detect whether the liquid has reached its flashpoint.
							<br>
							• MQ9: The Grove - Gas Sensor(MQ9) module is useful for gas leakage detection (in home and industry). It is suitable for detecting LPG, CO, CH4.
							<br>
							• Ultrasonic sensor: It is used to measure the distance between the lid of the container and the liquid stored in it.
							<br>
							• NodeMCU: NodeMCU is an open-source IoT platform. It includes firmware that runs on the ESP8266 Wi-Fi SoC from Espressif Systems, and hardware that is based on the ESP-12 module.

## Software Platforms
>• Arduino IDE: The open-source Arduino Software makes it easy to write code and upload it to the board. It runs on Windows, Mac OS X, and Linux. The environment is written in Java and based on Processing and other open-source software. This software can be used with any Arduino board.
							<br>
							• Adafruit Cloud: Adafruit.io is a cloud service - that just means we run it for you and you don't have to manage it. You can connect to it over the Internet. It's meant primarily for storing and then retrieving data but it can do a lot more than just that.
							<br>
							• IFTTT: If This Then That, also known as IFTTT, is a free web-based service to create chains of simple conditional statements, called applets. An applet is triggered by changes that occur within other web services such as Gmail, Facebook, Telegram, Instagram, or Pinterest.
               
