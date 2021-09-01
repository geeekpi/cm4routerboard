# cm4routerboard
Raspberry Pi Computer Module 4 internet extand board, make your Raspberry Pi CM4 a customized router, this repo contains firmwares and configuration files.

## Description
CM4 Router Board is an expansion board based on the Raspberry Pi Compute Module 4. It brings Raspberry Pi CM4 two full-speed gigabit network ports and offers better performance, lower CPU usage, and higher stability for a long time work compared with a USB network card.

The board still retains the characteristic GPIO pin header of Raspberry Pi, which makes it applicable for connecting other hat board such as Pi hats, sensors, and PoE hat board, and cooling fan, etc.

There is also a USB2.0 interface that can be connected to USB flash driver, USB keyboard, printers, WIFI modules,etc.

Besides, there is an OLED(0.91 inch) screen will help you to customize your Router Board's information display style.

It provides OpenWRT open-source router system. After a simple setup, it can be used as a router. It is also compatible with Raspberry OS, Ubuntu Server and other Raspberry Pi systems, even you can make this router board a retrogame machine at home.

The standard HDMI interface can help you configure the device and display operating information conveniently.

The powerful performance of BCM2711 4 core 1.5GHz Cortex-A72 and the rich software support in the Raspberry Pi community make this board a solid foundation for building high-performance gateways, smart routers, and home IoT platforms. It can also be connected to peripherals and used as a mini-NAS, wireless network bridge, or mini server which can be controlled via terminal.

If you need multiple LAN network ports like common routers, it is recommended to use a gigabit switch to expand the network ports, which will not affect its Internet performance.

5V DC Fan interface supports 5V cooling fan, it can alse support PWM protocol, that means you can control the speed of fan blades via PWM signal.

## Specifications 

* Compatible Module: Raspberry Pi Compute Module 4 series
* Support standard Raspberry Pi HAT interface
* Support POE HAT to supply power to the board
* Support POE HAT for external power supply
* Full-speed dual gigabit network interface
* Master-slave dual USB2.0 interface
* Micro SD card slot, used to support non-eMMC version of CM4
* Standard HDIM video output interface
* 0.91 inch I2C OLED display
* 5V DC fan interface(Support controlling via PWM signal)
* Ethernet: high-performance Gigabit ethernet controller RTL8111E chip, JXD 2111x G2406s chip as isolation transformer.
 - Port0: Compute Module 4 Built-In
 - Port1: PCI Express 1000BASE-T NIC
* GPIO: 40Pin GPIO compatible with Raspberry Pi
* Power Supply: USB-C(Type-C) 5V/3A interface
* Operating Temperature: 0℃~80℃
* Dimension: 146 x 80mm

## WiKi:
* ![Mechanical Drawing:](https://raw.githubusercontent.com/geeekpi/cm4routerboard/main/cm4-router-board%20mechanical%20drawing.png) 
* 52Pi CM4 Router Board WiKi: [ https://wiki.52pi.com/index.php/EP-0146 ]

## How to use factory image.
- Preparation
- 1. Etcher: a tool for flashing image to TF card.
- 2. Download factory image from github: `git clone https://github.com/geeekpi/cm4routerboard` 
- 3. Unzip image file or just flash it via etcher tool.
- 4. Insert TF card(MicroSD card) into the card slot on CM4 Router Board.
- 5. Connect the USB-C power supply into CM4 Router Board.
- 6. Open a browser in your Laptop or PC, navigate to `192.168.1.1` as default administration web URL, and input username: `root`, after login, please change password at first.
- 7. Configure the luci web app as you will and use the router as home router or IoT gateway.
