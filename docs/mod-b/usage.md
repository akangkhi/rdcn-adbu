---
layout: default
title: Usage
parent: Module B
nav_order: 1
---

# Module II Usage
{: .no_toc }

With Module II, 

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

### Powering Up

Plug in the Type-C cable to the primary board, which also houses the Display. Plugging it in the secondary board won't power the main board. It is purposedly designed as such.


The Type-C Cable can be plugged in a Laptop USB port, or a phone charger, or a power bank.
The operating voltage is 5V and it auto negotiates the voltage and the current to 3A.

### Verifying co-CPU

After pluggin in the Type-C Cable, the leds on the secondary board must also light up. If it doesn't the wires connecting both the boards might have come loose.

The detail description of each wire is given in the Hardware section.

### Understanding the options

On powering on, the display will greet with an Welcome Page, Please navigate through the Welcome page.

On the last welcome page, it will present an option if the welcome screen should be displayed everytime the board is powered on. Check the option if its not required to view the page again.


At the primary screen, the options for starting the system is shown, to get started, we need to know the baud of the COM port of the networking device/system we are connecting to, for wireless debugging. 

The provided dummy device has the baud at 115200. We select the correct baud, we further select the Input, which is UART1, or UART0 as per the connections made (please refer to the image below). And finally we select the output, which we will first try with the USB Dongle, hence select the Wireless Option. Once all the option are provided, please proceed with the connections.

### Connecting USB Dongle

When selecting the Wireless Option, the Serial output will be sent wirelessly through the 433MHz band to the USB Dongle. Please plug in the USB Dongle in the system (might require drivers to be installed), and start the Putty Program to connect to the COM port. 

### Using Telnet