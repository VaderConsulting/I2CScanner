# I2CScanner

Arduino sketch that walks I2C addresses 8–119 and prints every device that acknowledges on the bus. Written by Nick Gammon (20 April 2011); this is Dave Robinson's working copy from the Arduino archive. It uses `Wire` at 115200 baud and reports both decimal and hex addresses plus a device count.

**Language:** C++ / Arduino  
**Target:** Arduino with I2C (`Wire`); Leonardo waits for Serial  
**Output:** Arduino sketch

## Solution structure

| Project | Language | Type | Purpose |
|---------|----------|------|---------|
| `I2CScanner` | C++ / Arduino | sketch | Scan I2C and print found addresses on Serial |

## How to open

Open `I2CScanner.ino` in the Arduino IDE.

## Attribution and provenance

Original author: Nick Gammon (I2C Scanner, 20 April 2011). This repository is Dave Robinson's working copy for catalogue/reference; authorship stays with Nick Gammon.

## License

Original author terms apply to Nick Gammon's sketch. See `THIRD_PARTY_NOTICES.md`. The `LICENSE` file in this tree is the VaderConsulting MIT wrapper from import and does not re-attribute authorship.
