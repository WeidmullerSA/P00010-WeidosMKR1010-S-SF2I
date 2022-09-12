# ESP32_HttpPostLatency

This sketch measure the processing, sending, waiting server response and end connection times of the HTTP communication between client and server.

Developed by [Daniela Zaffalon, Weidmüller SA.](https://github.com/danielazaffalon)

## Dependencies

### Framework
- Developed over Framework version:
  - [Weidos-MKR-Package](https://github.com/WeidmullerSA/Weidos-MKR-package/releases/tag/1.0.0)

### Hardware
- hardware required:
  - [Weidos-MKR1010-A1](https://www.weidmuller.es/es/ventas/application_iot_centre/weidos_devices/index.jsp)

### Software
- software required:
  - [Ethernet](https://github.com/arduino-libraries/Ethernet)
  
## Usage

1) Install button on Interrupt Digital Input Pin.
2) Connect the Ethernet cable to the same ethernet network where the server is located.
3) Make sure you have a server within the same network that receives HTTP Post and enter the server IP, gateway and Port.
4) Press any button to send the HTTP Post with the input status to the server.
