[SerialFrame](https://medo64.com/serialframe/)
==============================================

This Framework laptop expansion card will show up on your system as a serial
device and allow for a fully isolated serial UART communication up to 460,800
baud rate.

Please note that this card is not using RS-232 but TTL voltage levels.

Also note that (in addition to GND, RXD, and TXD signals), you need to bring
an external 3.3-5V input due to card being insulated. While you can convert this
card to non-insulated variant, I do not recommend it as any ground loop could
put your computer at risk.


## UART Pinout

| # | Ref | Description                     |
|--:|-----|---------------------------------|
| 1 | GND | Ground connection.              |
| 2 | RXD | Receive.                        |
| 3 | TXD | Transmit.                       |
| 4 | -   | Not connected.                  |
| 5 | V+  | Either 3.3V or 5V power supply. |

---
*You can check my blog and other projects at [www.medo64.com](https://www.medo64.com/electronics/).*
