# Bring Up Test

##### Make sure that the board
* is manufactured properly
* is able to power up
* is able to reset
* is programmable
* doesn't heat up
* doesn't burn up
* has sensible current consumption
* or any other major issues

##### Legend
| Result | Icon |
| -- | -- | 
| Pass | :white_check_mark: |
| Fail | 🔴|
| TODO | ⚠️ |
| Waived or n/a | :information_source: |


| Equipment Class | Test Item | Requirement | Procedure | Measurements | Comment | Res |
| -- | -- | -- | -- | -- | -- |-- |
| 0 | PIC 0 | Pictures of both sides of PCBA | n/a | n/a | | :white_check_mark: |
| 0 | DNM 0 | Assembly equals BOM | n/a | n/a | | :white_check_mark: |
| 0 | POL 0 | Correct component polarity | n/a | n/a | | :white_check_mark: |
| 0 | TOMB 0 | No tombstoneing | n/a | n/a | | :white_check_mark: |
| 0 | SHORT 0 | No shortcircuit | Measure more than 0 Ohm between voltage rails | n/a | | :white_check_mark: |
| 0 | PWR 0 | Power up. No smoke | Power up with current limit | n/a | | :white_check_mark: |
| 0 | PWR 1 | Power up. No smoke. Status LED lit | Power up with NO current limit | n/a | | :white_check_mark: |
| 0 | REG 0 | Correct voltage from regulators. Vout +/- 10% | n/a| n/a | | :white_check_mark: |
| 0 | PROG 0 | All MCUs programmable | n/a | n/a | | :white_check_mark: |
| 0 | CURR 0 | Sensible current consumption | Measure with multimeter or check PSU | n/a | | :white_check_mark: |
| 0 | TEMP 0 | Component temperature < 50 degree celcius | Take pictures with temperature camera | n/a | | :white_check_mark: |
| 0 | OSC 0 | Oscillator frequency within (min, max) | Measure over oscillator with near field probe or output oscillator frequency on GPIO | n/a | | :white_check_mark: |
