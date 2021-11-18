---
layout: default
title: Parcel
nav_order: 99
has_children: false
permalink: /package
---

# Parcel Package Contents
{: .no_toc }


Two item, that will be required to test module-II is sent along with the parcel, but in a different box labelled "Netgear".

Their usage/purpose is mentioned in the documentaion. Please use the search option.

{: .fs-6 .fw-300 }


## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## Type C Power cable

<br>

Both Module-I and Module-II are powered via USB Type-C. <br>
USB Type-C requires certain conditions to be followed by the power cable as well as the downstream devices to negotiate the voltage/current/power. Both Module-I and II are tested with this USB Type-C cable.

![Alt text](package/assets/typec.png?raw=true "Power Adapter")

***

## Dummy RS232/UART/RS485 device

<br>

Module II will require an UART device to work with. <br>
This DBC device is an fibre ONT, mostly used in customer network premises. Unlike the enterprise grade networking devices, This device doesn't have a dedicated COM port.But it has a port reserved for such purposes. Modification is done to the board to expose the COM port. This COM port supports only UART at 115200 baud. 
The wire color codes are as follows:


| Sl | Color | Function |
|--|--|--|
| 1 | Green | TX |
|2|Blue|RX|
|3|Black|GND|
|4|Red|Not Used|


![Alt text](package/assets/ont.png?raw=true "Power Adapter")

***

## Power Adapter

![Alt text](package/assets/adapter12v.png?raw=true "Power Adapter")

***

## Module I
![Alt text](package/assets/moda.png?raw=true "Power Adapter")

***

## Module II
![Alt text](package/assets/modb.png?raw=true "Power Adapter")

***

## Programmer
![Alt text](package/assets/prog.png?raw=true "Power Adapter")

***