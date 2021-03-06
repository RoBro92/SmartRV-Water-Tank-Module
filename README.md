 [![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/O5O4AKQ37)

# SmartRV Water Tank Module
**A ESP based water tank module for a Camper/RV**

All feature requests are tracked in the GitHub issue tracker. 
[Feature Requests](https://github.com/RoBro92/feature-requests/issues)

This water tank module is designed to fill a gap in the market for accessible smart water tank monitoring. Other systems such as Pico and Victron do exist however there cost can be prohibitive. This module is based off the ESP8266/32 by Espressif & is designed to work standalone or as part of a network to provide accurate and realtime updates for water tank level and temperature. It also provides a relay designed to interface with motorized ball valves either 2/3 wire and will allow remote draining of tanks without having to leave the vehicle. 

The module has been kept as compact as possible and allows for a direct connection to 12v or 24v vehicle systems. 


**If you want to support the development you can purchase this board as a DIY kit or assembled from my Ko-Fi Shop [SmartRV Shop](https://ko-fi.com/smartrv/shop)**

## **I have developed two seperate versions of this module**

[V1 is THT and is suitable for at home soldering](#tht)

[V2 is SMD and is designed to be assembled by a PCB manufacturer](#smd)





### THT

# **V1.2**
This release represents the final revision any further changes should be requested in the [Feature Requests](https://github.com/RoBro92/feature-requests/issues) section

# **Changes**
- [x] - Added reverse polarity protection
- [x] - Added LED indicators for power and relay
- [x] - Updated repository with Gerber production files

# **Features**
- [x] - Removeable WemosD1 chip (ESP8266)
- [x] - Onboard power regulation
- [x] - Variable voltage input 8v-36v
- [x] - Compact form factor
- [x] - DS18b20 temperature sensor
- [x] - Resistive water level sensor
- [x] - 10A relay for water valve control
- [x] - LED Indicator for Power-ON


# **Upcoming Changes**

- [ ] - Create 3D printable case


# **Images**
<table>
  <tr>
    <td>3D Model</td>
  </tr>
  <tr>
    <td><img src="V1%20THT/images/3dmodelfront.jpg" height=480></td>
  </tr>
 
 </table>
<table>
  <tr>
         <td>Schematic</td>
     <td>PCB Layout</td>

  </tr>
  <tr>
   <td><img src="V1%20THT/images/schematic.jpg" height=480></td> 
   <td><img src="V1%20THT/images/pcblayout.jpg" height=480></td>    
  </tr>
 </table>

<table>
  <tr>
    <td>PCB Front v1.0</td>
     <td>PCB Rear v1.0</td>
  </tr>
  <tr>
    <td><img src="V1%20THT/images/pcbfront.jpeg" height=480></td>
    <td><img src="V1%20THT/images/pcbrear.jpeg" height=480></td>
  </tr>
 </table>

# **WARNING**
This board does not have any fuse protection as such this must be provided externally.

___

### SMD

# **V2.0**
This version will be primarily designed to be a production, standalone product with either bluetooth app control or a touchscreen interface/display. 

It will also feature an ESP32 Module for several reasons;
- Bluetooth connection with AIO board to act as an additional wireless tank sensor
- Lower power consumption if being used with a battery
- Newer technology

# **Changes**
- [x] - Added initial schematic and PCB layout with images
- [x] - Add reverse polarity protection

# **Features**
- ESP32 Wroom 32D SMD 
- Onboard power regulation
- Variable voltage input 8v-36v
- Compact form factor
- DS18b20 temperature sensor
- Resistive water level sensor
- 10A relay for water valve control
- LED Indicator for Relay-ON
- LED Indicator for Power-ON
- Revers polarity protection


# **Upcoming Changes**

- [ ] - Create 3D printable case
- [ ] - Fuse protection
- [ ] - Bluetooth app
- [ ] - Bluetooth communication
- [ ] - Additional Temp Sensor
- [ ] - External display 


# **Images**
<table>
  <tr>
    <td>Schematic</td>
     <td>PCB Layout</td>
  </tr>
  <tr>
    <td><img src="V2%20SMD/Images/schematic.jpg" height=480></td>
    <td><img src="V2%20SMD/Images/pcblayout.jpg" height=480></td>
  </tr>
 </table>

<table>
  <tr>
    <td>3D Model Front</td>
     <td>3D Model Rear</td>
  </tr>
  <tr>
    <td><img src="V2%20SMD/Images/3dfront.jpg" height=480></td>
    <td><img src="V2%20SMD/Images/3dback.jpg" height=480></td>
  </tr>
 </table>

# **WARNING**
This board does not have any fuse protection as such this must be provided externally.

