# BlackBox Modbus Client Library for LabVIEW
This is an implementation of [this protocol](https://github.com/plasmapper/blackbox/tree/main/modbus.md) client for LabVIEW.

## Requirements
LabVIEW 2015 and higher.

[Modbus Client Library](https://github.com/plasmapper/modbus-client-labview) ([VIPM package](https://www.vipm.io/package/plasmapper_lib_pl_modbus_client/))

## Features
Full functionaltity of the [BlackBox Modbus protocol](https://github.com/plasmapper/blackbox/tree/main/modbus.md).  
Actual device class should inherit `PL BlackBox Modbus Client.lvclass`, optionally override `Check Firmware Compatibility.vi` and implement actual device functions using Modbus read/write functions from the base class `PL Modbus Client.lvclass`.

## Examples
### BlackBox Configurator.vi
Example VI that demonstrates all library features.

### [BlackBox Firmware and Software Examples](https://github.com/plasmapper/blackbox/tree/main/examples)