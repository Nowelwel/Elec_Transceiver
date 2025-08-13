# Dokumentasi Transceiver
Folder ini berisi semua file hardware untuk proyek **Transceiver Board**. Gunakan Software di bawah ini untuk akses file Hardware
- [KiCad](https://kicad.org/)
- [Eagle](https://www.autodesk.com/products/eagle) 

## 📃 Schematic
Berikut adalah schematic dari Transceiver Board 2.0. 
![Schematic](../images/schematic.jpg)

## BOM
Berikut adalah BOM board Transceiver 2.0.

|References|Quantity|Package|Value|Desc|
|:-:|:------:|:----:|:---:|:--:|
|C1|1|0805|100nF|Capacitor|
|R13, R16-R18, R21-R24|8|0805|330R|Resistor|
|R19, R20, R30, R31|4|0805|10K|Resistor|
|LED1, LED 2|2|1206| - | LED|
|IC1|1|SO14|74HCT14D|Hex inverter with Schmitt-trigger inputs|
|IC2|1|SO14|74HCT125D|Quad buffer|
|D1|1|SOT-23|SRV05-4|Diode array|
|U$1|1|TRANSCEIVER_2.0|TRANSCEIVER_2.0|Socket|
