# IOT_Project

## Summary

This IoT project is designed to test our skill in understanding, and developing, IoT-based devices and applications. We will do so in a way that is correct, modular, and maintainable. We will use and learn about multiple technologies during this project. The aim of this project is to make the pynq board into a IoT device that uses openremote to visualize the data the pynq board recives/makes. In this project we will be making use of Docker and openremote as well as Github and PuTTY. Docker is used for running the Openremote container on the Pynq board. PuTTY gives us the ability to use the CLI(command line interface) to install all the tools and pakages for this project

## Pynq

PYNQ (Python Productivity for ZYNQ) is an open-source project from Xilinx that makes it easy to design embedded systems with Xilinx Zynq Systems on Chips (SoCs). The PYNQ board is based on the Zynq SoC, which contains a dual-core ARM Cortex-A9 processor and an FPGA fabric. The board is designed to be programmed using Python, which allows developers to take advantage of the high-level programming language to create embedded systems with a high degree of flexibility and control. PYNQ also provides a library of pre-built overlay IP that allow users to easily add hardware-accelerated functions like video processing, image processing, and machine learning to their designs.

## Docker

Docker is a containerization platform that allows you to package and deploy software in a portable and consistent manner. A container is a lightweight, stand-alone executable package that includes everything needed to run a piece of software, including the code, runtime, system tools, libraries, and settings. Docker provides a way to manage the lifecycle of containers, including the creation, deployment, and destruction of containers. It also provides a centralized repository for container images, called the Docker Hub, which allows developers to share and distribute their containerized applications.

Docker's main advantage over other containerization solutions is its flexibility and portability. Since Docker containers package all the dependencies and configuration settings needed to run an application, they can be easily moved from one environment to another without the need for additional configuration. This means that a containerized application can be run on a developer's laptop, on a test server, and in production, with little to no changes required. Docker is also widely adopted in the industry, and many cloud providers offer integrated support for Docker, which allows you to easily deploy and run your containerized applications on the cloud.

## Openremote

OpenRemote is an open-source platform for building and deploying Internet of Things (IoT) solutions. It provides a flexible and extensible architecture for connecting devices, sensors, and actuators to the internet, and for creating applications that can interact with and control those devices. OpenRemote provides a web-based interface for managing and configuring devices, and it also includes a rules engine that allows you to create automation and control rules based on the data from your devices. The platform also includes a library of pre-built connectors and drivers that can be used to connect to a wide variety of devices and protocols, including Z-Wave, Zigbee, BACnet, Modbus, and many others. The OpenRemote platform can run on a variety of hardware and software platforms, including on-premises servers, cloud-based services, and edge devices such as gateways and microcontroller boards. It is designed to be highly scalable and can support thousands of devices and sensors.

## Putty 

PuTTY is a free and open-source terminal emulator, serial console, and network file transfer application. PuTTY is mainly used as a SSH client, which allows you to connect to remote servers and devices over a network and run commands and transfer files as if you were sitting directly in front of them. PuTTY supports various authentication methods including password, public key and keyboard-interactive, and also supports several encryption methods, such as AES, 3DES, and Blowfish.

In addition to SSH, PuTTY also supports other protocols such as Telnet and serial connections. The serial connection feature allows PuTTY to be used as a terminal emulator for serial devices such as microcontrollers, embedded systems, and other devices that use a serial connection to communicate. This can be useful for debugging, testing, and programming these devices.
