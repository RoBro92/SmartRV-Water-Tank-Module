 [![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/O5O4AKQ37)

# SmartRV Water Tank Module
**A Wemos based water tank module for a Camper/RV**

All feature requests are tracked in the GitHub issue tracker. 
[Feature Requests](https://github.com/RoBro92/feature-requests/issues)

This water tank module is designed to fill a gap in the market for accessible smart water tank monitoring. Other systems such as Pico and Victron do exist however there cost can be prohibitive. This module is based off the ESP8266/32 by Espressif & is designed to work standalone or as part of a network to provide accurate and realtime updates for water tank level and temperature. It also provides a relay designed to interface with motorized ball valves either 2/3 wire and will allow remote draining of tanks without having to leave the vehicle. 

The module has been kept as compact as possible and allows for a direct connection to 12v or 24v vehicle systems. 

**V1.0**
This is the first revision of the Water Tank Module pre production.

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
- Replace components with SMD equivelant
- Add reverse polarity protection
- Create 3D printable case
- Fuse protection
- Bluetooth app
- Bluetooth communication
- Additional Temp Sensor
# **Images**
<table>
  <tr>
    <td>3D Model</td>
     <td>PCB Layout</td>
  </tr>
  <tr>
    <td><img src="images/Watermodule3dv1.jpg" height=480></td>
    <td><img src="images/WatermodulePCBv1.jpg" height=480></td>
  </tr>
 </table>



# **WARNING**
This board does not have any fuse protection as such this must be provided externally.





