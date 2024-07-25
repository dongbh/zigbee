# zigbee firmware and releated

EmberZNet (EZSP) Zigbee 3.0 / Zigbee Coordinator (NCP) firmmware for Silicon Labs EFR32MG13 and EFR32MG21 DIY USB dongle.

## Name information:

ncp-uart-MODULE-FLOWCONTROL-BAUD.gbl
ncp-uart: means this is a ncp firmware.
MODULE: mg13/mg210l
       mg13: efr32mg13p732
       mg210l: mgm210l022JNF
FLOWCONTROL: hw/xonoff/noflowcontrol
       usb2zigbee device can use hw or noflowcontrol
       ethernet2zigbee device must use noflowcontrol

## mg13(efr32mg13p732) module
| Configuration Parameter  | Value |
|---------------|-----------|
| TX  | PA0 |
| RX  | PA1 |
| RTS | PF4 |
| CTS | PA2 |
| LED | PC7 |
| SW1 | PF3 |

## mgm210l module
| Configuration Parameter  | Value |
|---------------|-----------|
| TX  | PC01 |
| RX  | PC00 |
| RTS | PC03 |
| CTS | PC02 |
| LED | PC04 |
| SW1 | PD01 |


