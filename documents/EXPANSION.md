The boards feature a standard connector for providing power, GPIO and communication protocols. It is placed in the top of the board and contains 36 pins. The pins provide a standard feature, but they can have alternative purposes, depending on the board.
Pin descriptions:

| Pin | Signal | Description | Observations |
| ------ | ------ | ------ | ------ |
| 1 | GND | Board ground reference 
| 2 | VSYS | +3V3 regulated supply | Nodes provide this supply |
| 3 | VEXT | +5V regulated supply | Capes provide this supply |
| 4 | VBAT | LiIon + cell input | Nodes use this supply |
| 5 | NTC | LiIon NTC input | Nodes use this supply |
| 6 | BATGND | LiIon - cell input | Nodes use this supply |
| 7 | NRST | Reset signal | General board reset signal |
| 8 |
| 9 |
| 10 |
| 11 | UART0_TXD | UART TXD | Main uart for debug and comms|
| 12 | UART0_RXD | UART RXD |
| 13 | CAPE_EN1 | Enable gate for cape power down | Can be used as GPIO |
| 14 | CAPE_EN2 |
| 15 | UART1_TXD |
| 16 | UART1_RXD |
| 17 | I2C_SCL |
| 18 | I2C_SDA |
| 19 | IRQ0 | Hw interrupt signal | Nodes use this pin |
| 20 | IRQ1 |
| 21 | GPIO0 |
| 22 | GPIO1 |
| 23 | UART2_TXD |
| 24 | UART2_RXD |
| 25 | SPI_CLK |
| 26 | SPI_NCS |
| 27 | SPI_MOSI |
| 28 | SPI_MISO |
| 29 | CAN_TX |
| 30 | CAN_RX |
| 31 | GPIO2 |
| 32 | GPIO3 |
| 33 | GPIO4 |
| 34 | GPIO5 |
| 35 | GPIO6 |
| 36 | GPIO7 |
