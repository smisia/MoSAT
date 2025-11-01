# Purpose of the satellite
The main objective is to create a device for learning purposes with sesnsors, which montiros it's current environmental parameters. The implementation should carry the possiblity to later expand the functionality and design to make a fully functional launch ready CubeSAT.

# Requirements:
<br/> - Must be around 1kg
<br/> - It must use the 1U configuration (10x10x10 cm)
<br/> - Must use only 3.3V and 5V bus voltages
<br/> - Must comply with CDS and ECSS (The machanical design is an exception since for hobby usage it will be made out of PLA)
<br/> - This list could expand in the future

Note: There is a possibility that the final product will differ from the requirements to some extent, but I try to stick these constrains as much as possible.

# Currenty used literatures (will expand and the project progresses)
CubeSat Design Specification REV 14.1

## TODO list
- [ ] System design
- [ ] Create prototype with OBC (STM32CH32F103) + Battery (Li-ion/LiPo) + some sensors (temperature, voltage/current, IMU, magnetometer, sun sensors, (GPS))
- [ ] Integrate telemetry (with nRF24 transceiver)
- [ ] Integrate power system
- [ ] Fit to mechanical design
