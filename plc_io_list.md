|                       | OpenPLC adres | pinnaam    | functie              | commentaar                                           |
|:--------------------- |:------------- |:---------- |:-------------------- |:---------------------------------------------------- |
| **digital in**        | %IX0.0        | A5         | licht hall/alles uit | korte druk/ lange druk                               |
|                       | %IX0.1        | A6         | keuken               |                                                      |
|                       | %IX0.2        | A7         | licht eetplaats      |                                                      |
|                       | %IX0.3        | A8         | living               |                                                      |
|                       | %IX0.4        | A9         | praktijk1            |                                                      |
|                       | %IX0.5        | A10        | Praktijk 2           |                                                      |
|                       | %IX0.6        | A11        | licht trap           | bewegingsmelder                                      |
|                       | %IX0.7        | A12        | licht wc beneden     |                                                      |
|                       | %IX1.0        | A13        | licht wc boven       |                                                      |
|                       | %IX1.1        | A14        | licht buiten 1       |                                                      |
|                       | %IX1.2        | A15        | licht buiten 2       |                                                      |
|                       | %IX1.3        | I16        | licht buiten 3       |                                                      |
|                       | %IX1.4        | I17        | licht buiten 4       | bewegingsmelder                                      |
|                       | %IX1.5        | I18        | scherm op            |                                                      |
|                       | %IX1.6        | IN0        | scherm neer          |                                                      |
|                       | %IX1.7        | IN1        | kelder               |                                                      |
|                       |               |            |                      |                                                      |
| **digital out**       | %QX0.0        | R0         | licht trap           | rechtstreeks 220v                                    |
|                       | %QX0.1        | R1         | licht wc beneden     | rechtstreeks 220v                                    |
|                       | %QX0.2        | R2         | licht wc boven       | rechtstreeks 220v                                    |
|                       | %QX0.3        | R3         | licht buiten 1       | rechtstreeks 220v                                    |
|                       | %QX0.4        | R4         | licht buiten 2       | rechtstreeks 220v                                    |
|                       | %QX0.5        | R5         | licht buiten 3       | rechtstreeks 220v                                    |
|                       | %QX0.6        | R6         | licht kelder         | rechtstreeks 220v                                    |
|                       | %QX0.7        | R7         | licht slaapkamer 1   | rechtstreeks 220v                                    |
|                       | %QX1.0        | R8         | licht slaapkamer 2   | rechtstreeks 220v                                    |
|                       | %QX1.1        | R9         | licht slaapkamer 3   | rechtstreeks 220v                                    |
|                       | %QX1.2        | R10        | scherm op            | rechtstreeks 220v                                    |
|                       | %QX1.3        | R11        | scherm neer          | rechtstreeks 220v                                    |
|                       | %QX1.4        | R12        | licht zolder         | rechtstreeks 220v                                    |
|                       | %QX1.5        | R13        | licht eetplaats      | rechtstreeks 220v                                    |
|                       | %QX1.6        | R14        |                      |                                                      |
|                       | %QX1.7        | R15        |                      |                                                      |
|                       | %QX2.0        | D0         | alles uit            | 24v naar alles uit impulsrelais'                     |
|                       | %QX2.1        | D1         | hall                 | 24v naar relais'                                     |
|                       | %QX2.2        | D2         | keuken               | 24v naar relais'                                     |
|                       | %QX2.3        | D3         | waskot               | 24v naar relais'                                     |
|                       | %QX2.4        | D4         | living               | 24v naar relais'                                     |
|                       | %QX2.5        | D5         | werkkot              | 24v naar relais'                                     |
|                       | %QX2.6        | D6         | praktijk1            | 24v naar relais'                                     |
|                       | %QX2.7        | D7         | Praktijk 2           | 24v naar relais'                                     |
|                       | %QX3.0        | D8         |                      |                                                      |
|                       | %QX3.1        | D9         |                      |                                                      |
|                       | %QX3.2        | D10        |                      |                                                      |
|                       | %QX3.3        | D11        |                      |                                                      |
|                       | %QX3.4        | D12        |                      |                                                      |
|                       | %QX3.5        | D13        |                      |                                                      |
|                       | %QX3.6        | D14        |                      |                                                      |
|                       | %QX3.7        | D15        |                      |                                                      |
|                       |               |            |                      |                                                      |
| **Analog in**         | %IW0          | A0         |                      |                                                      |
|                       | %IW1          | i2c        | lichtsensor          |                                                      |
|                       |               |            |                      |                                                      |
| **Analog Out**        | D16           | %QW0       | wandverlichting      | 24V PWM rechtstreeks                                 |
|                       |               |            |                      |                                                      |
| **Holding Registers** |               | %QW1 - ... |                      | virtuele output gebruikt als modbus holding register |
|                       |               |            |                      |                                                      |
