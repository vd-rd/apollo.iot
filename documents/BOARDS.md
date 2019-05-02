### Types

### SBC 
These boards are more powerful and can be used with higher operating systems (Linux, Windows IoT etc.) but are still battery friendly if desired.
Boards developed in this scope:
 - [sbc_allwinner_a13](https://github.com/vd-rd/sbc_alw_a13) - (no ethernet)
 - [sbc_allwinner_v3s](https://github.com/vd-rd/sbc_alw_v3s) 
 - [sbc_at91_rm9200](https://github.com/vd-rd/sbc_at91rm9200)
 - [sbc_at91_9260](https://github.com/vd-rd/sbc_at91sam9260)
 - [sbc_intel_x1020](https://github.com/vd-rd/sbc_quark_x1000) - (pci express)
 - [sbc_nxp_mx6ul]()
 
### Node
Nodes have the role of processing data from IO, sensors and other sources and interacting with other nodes and/or the cloud.
Boards developed in this scope:
  - [node_stm32_high]() - STM32 F4/F7 processing node
  - [node_stm32_medium](https://github.com/vd-rd/hw_node_stm32_medium) - STM32 F1/F2/F3 processing node (no comms)
  - [node_stm32_low]() - STM32 L1 processing node (no comms)
  - [node_esp32]() - ESP32 WiFi/BT processing node

### Cape
Capes have the purpose to provide the processing boards with additional communication protocols, sensing, IO or power features. This scope is accomplished by connecting via the Interconnect Bus with the proper signals. 
Boards developed in this scope:
  - [cape_mains](https://github.com/vd-rd/hw_cape_mains) - isolated step-down mains power supply 
  - [cape_poe](https://github.com/vd-rd/hw_cape_poe) - isolated step-down PoE and ethernet connectivity 
  - [cape_gps](https://github.com/vd-rd/hw_cape_gps) - GPS telemetry for precise positioning
  - [cape_gsm](https://github.com/vd-rd/hw_cape_gsm) - GSM communications for long range data transfer
  
