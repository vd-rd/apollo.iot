### Types

### SBC 

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
  
