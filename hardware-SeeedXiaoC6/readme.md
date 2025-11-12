# Seeed Xiao ESP32-C6 PCB Design

This version is for [Seeed Xiao ESP32-C6](https://wiki.seeedstudio.com/xiao_esp32c6_getting_started/), based on the `FeatherS3` revision.

PCB design by [@IreuN](https://github.com/ireun).

> **Note:** This design is untested and has never been produced. It is provided as-is, without any kind of warranty.

## Changes

* Added TestPoints (GND, 3V3, 12V)
* Added additional capacitor C3 on 3V3 output of TPS82130
* Added ability to mount XIAO directly or through header
* Reduced to 2 layers only
* Moved signal pin to the middle of JST connector
* Added a place for an IR diode, making it possible to use it when some functions are unavailable to set by CN-REMO but are available to an IR remote

## Images

![PCB 3D View](images/pcb-3D.png)
![PCB Front](images/pcb-front.png)
![PCB Rear](images/pcb-rear.png)