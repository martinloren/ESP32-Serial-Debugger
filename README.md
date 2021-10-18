# ESP32-Serial-Debugger
A compact serial port debugger with ESP32 (WiFi). This device act like a serial port to send and receive data through WiFi to your Web Browser.

It can work in AP (create an indipendent WiFi Access Point) or STA mode (connect to your existing WiFi network) where a phone or PC can connect and debug data with a Web Browser.

![Serial Debugger](Schematics/ESP32_Connections_V1.0.png)

- Web User Interface (read how to use below)
- Possibility to configure the serial port on-the-fly
- Send/Receive data in real-time
- Serial Max Speed: 115.000 baud (in the free version)

## Advantages
- You don't need to install a software on Windows
- You don't need to restart your serial terminal since the software crash, freeze or the serial port freeze
- You don't need even a PC, you can use a Tablet or a Phone, or you just add a tablet as an additional dedicated screen to your working bench
- You don't need to have a WiFi network, it can create a specific hot spot, use it on-the-fly wherever you are

## Screenshots
<p align="center">
    <img src="Screenshots/Screenshot_1.png" alt="Screenshot" width="600"/>
</p>

[→ Sample Video](Screenshots/Video_1.mp4)

## TODO
- Automatic serial data generator (to test serial receivers)
- Decode data in HEX (beside ASCII)
- Suggestions?

## Flashing the ESP32 Firmware
Check out the guide [here](https://www.martinloren.com/guides/fashing-esp32/) 

### V1.1
- Bug fixed
- Added terminal colors (red, green, yellow)
- Enlarged buffer (8KB/200ms)
- Improved UI
- Added support for phone/tablets browsers

### V1.0
- First Release

## How to use
When the ESP is powered it creates a Wifi access point with SSID like **ESP-SERIAL-F62684**. 
- Connect to it with the phone or PC (default password: **123456789**)
- Open the browser (everything except Internet Explorer) at address **192.168.4.1**
- In the Settings panel you can configure the Serial Port settings and the WiFi mode
 
 
