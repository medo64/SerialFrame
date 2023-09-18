[UartIsoWork](https://medo64.com/uartisowork/)
==============================================

This Framework laptop expansion card will show up on your system as a serial
device and allow for a fully isolated serial UART communication up to 3 Mbaud
rate.

Please note that this card is not using RS-232 but TTL voltage levels.


## UART Pinout

| # | Ref | Description                     |
|--:|-----|---------------------------------|
| 1 | RXD | Receive                         |
| 2 | GND | Ground connection               |
| 3 | TXD | Transmit                        |


### Wiring

To connect to this board, one has to use 3-pin JST XH connector. The following
table represents the pinout, pin 1 being on the left as looking into the
expansion card.

As board is insulated, both power and ground wires MUST be connected in order
for communication to work.

| # | Ref | Color  | Purpose       |
|--:|-----|--------|---------------|
| 1 | RXD | Yellow | Receive       |
| 2 | GND | Black  | Ground        |
| 3 | TXD | Orange | Transmit      |

PS: Colors are just a suggestion and it's not necessary to have them match the
table.

PPS: As power consumption is below 10 mA, wires can be almost any AWG. I would
recommend using 24 AWG wire 0.25 mm² as they allow for greater compatibility
with other connectors.

---
*You can check my blog and other projects at [www.medo64.com](https://www.medo64.com/electronics/).*
