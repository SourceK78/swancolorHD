# swancolorHD custom pcb

## About
This board is a customized version of the swancolorHD main board developed by [zwenergy](https://github.com/zwenergy).  

The changes are as follows:  
- Adding a main power switch  
- Change to USB Type-C power supply   
- Change controller from SNES to PS/PS2  
- Changed connection with WonderSwan color pcb to FFC ([pogo pin pcb](../pogo-pin_pcb/) required)  
- Supports bluetooth connectivity for swantroller([See this thread](https://x.com/SourceK_mnst/status/1868656980438753522))  

### PCB BOM
| **Reference** | **Part** | **Link** |
|---------|------|------|
|FPC1, FPC2 | FFC connector with 24 pins, 0.5mm pitch, bottom contacts | [LCSC](https://lcsc.com/product-detail/FFC-FPC-Connectors_XUNPU-FPC-05F-24PH20_C2856805.html)|
|U1      | Arduino Nano | [AliExpress](https://aliexpress.com/item/1005002966043359.html)|
|U2 [*hint](#hint)| Seeed Studio xiao ESP32-C3 | [AliExpress](https://aliexpress.com/item/1005007084388623.html)|
|U4      | TLV62569DBVR | [LCSC](https://www.lcsc.com/product-detail/DC-DC-Converters_Texas-Instruments-TLV62569DBVR_C141836.html)|
|U5      | Tang Nano 9k | [AliExpress](https://aliexpress.com/item/1005004275570427.html)|
|JOY1    | PS/PS2 controller connector 90° female | [AliExpress](https://ja.aliexpress.com/item/1005006039721141.html)|
|CN1 - CN3 | JST PH 2.0 connector (wire set) | [AliExpress](https://ja.aliexpress.com/item/1005007165519817.html)|
|JP1 - JP3 | pin header 1x02 2.54mm pitch & jumper cap | - |
|SW1 [*hint](#hint)| 2.54mm pitch spdt slide switch | - |
|C1      | 4.7 uF capacitor (1206) | - |
|C2      | 22 uF capacitor (1206) | - |
|R1      | 150 kΩ resistor (1206) | - |
|R2      | 100 kΩ resistor (1206) | - |
|R13, R14 | 1 kΩ resistor (1206) | - |
|L1      | 2.2uH Inductors (SMD) | [LCSC](https://www.lcsc.com/product-detail/Tactile-Switches_XUNPU-TS-1088-AR02016_C720477.html)|
|Q1 - Q12 | N-channel MOSFET 2N7002 (SOT-23) |[LCSC](https://lcsc.com/product-detail/MOSFETs_Jiangsu-Changjing-Electronics-Technology-Co-Ltd-2N7002_C8545.html)|

##### *hint  
Required if you want to connect swantroller via bluetooth.  

### Other Parts  
| **Part** | **Link** |
|----------|----------|
| 24pin 0.5mm pitch Forward Direction(Type-A) FFC 15cm (2 pcs)| [AliExpress](https://ja.aliexpress.com/item/1005006021065589.html)|
| USB Type-C power supply connector female | [AliExpress](https://ja.aliexpress.com/item/1005006297697300.html)|
| self-locking switch 3-6V 8mm dia | [AliExpress](https://ja.aliexpress.com/item/1005005628118782.html)|
| battery contacts (TAKACHI:IT-4SP) (2 pcs)| [Kyohritsu eleshop](https://eleshop.jp/shop/g/gN2A114/)|
| header socket 1x40  (2 pcs)| - |
| header socket 1x08  (2 pcs)| - |