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


### Wiring

To connect to this board, one has to use 5-pin JST PH connector. The following
table represents the pinout, pin 1 being on the left as looking into the
expansion card.

As board is insulated, both power and ground wires MUST be connected in order
for communication to work.

| # | Ref | Color  | Purpose       |
|--:|-----|--------|---------------|
| 1 | GND | Black  | Ground        |
| 2 | RXD | Yellow | Receive       |
| 3 | TXD | Orange | Transmit      |
| 4 | -   | -      | Not connected |
| 5 | V+  | Red    | Power         |

PS: Colors are just a suggestion and it's not necessary to have them match the
table.

PPS: As power consumption is below 10 mA, wires can be almost any AWG. I would
recommend using 24 AWG wire 0.25 mm² as they allow for greater compatibility
with other connectors.

---
*You can check my blog and other projects at [www.medo64.com](https://www.medo64.com/electronics/).*
