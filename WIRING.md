### SerialFrame Wiring

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
