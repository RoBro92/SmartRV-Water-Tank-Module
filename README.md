 [![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/O5O4AKQ37)

# SmartRV Water Tank Module
**A Wemos based water tank module for a Camper/RV**

All feature requests are tracked in the GitHub issue tracker. 
[Feature Requests](https://github.com/RoBro92/feature-requests/issues)

This water tank module is designed to fill a gap in the market for accessible smart water tank monitoring. Other systems such as Pico and Victron do exist however there cost can be prohibitive. This module is based off the ESP8266/32 by Espressif & is designed to work standalone or as part of a network to provide accurate and realtime updates for water tank level and temperature. It also provides a relay designed to interface with motorized ball valves either 2/3 wire and will allow remote draining of tanks without having to leave the vehicle. 

The module has been kept as compact as possible and allows for a direct connection to 12v or 24v vehicle systems. 

**If you want to support the development you can purchase this board as a DIY kit or assembled from my Ko-Fi Shop [SmartRV Shop](https://ko-fi.com/smartrv/shop)**


# **V1.1**
This is the initial release and has been tested to work as expected.

# **Changes**
- Changed FTDI header to 2.54 pitch (Important)
- Updated relay to D2


# **Features**
- Removeable WemosD1 chip (ESP8266)
- Onboard power regulation
- Variable voltage input 8v-36v
- Compact form factor
- DS18b20 temperature sensor
- Resistive water level sensor
- 10A relay for water valve control
- LED Indicator for Relay-ON


# **Upcoming Changes**

- [ ] - Replace components with SMD equivelant
- [ ] - Add reverse polarity protection
- [ ] - Create 3D printable case
- [ ] - Fuse protection
- [ ] - Bluetooth app
- [ ] - Bluetooth communication
- [ ] - Additional Temp Sensor


# **WARNING**
This board does not have any fuse protection as such this must be provided externally.

# **Images**
<table>
  <tr>
    <td>3D Model</td>
     <td>PCB Layout</td>
  </tr>
  <tr>
    <td><img src="images/v1.1_pcb_layout.jpg" height=480></td>
    <td><img src="images/PCB%20Layoutv1.1.jpg" height=480></td>
  </tr>
 </table>

<table>
  <tr>
    <td>PCB Front</td>
     <td>PCB Rear</td>
  </tr>
  <tr>
    <td><img src="images/pcbfront.jpeg" height=480></td>
    <td><img src="images/pcbrear.jpeg" height=480></td>
  </tr>
 </table>

# **WARNING**
This board does not have any fuse protection as such this must be provided externally.





