# UM3561-Siren-Generator
Can play either a Police Siren, Ambulance Siren or Fire Engine Siren when triggered.

**Full Video:**
[![Siren Generator](https://img.youtube.com/vi/J3Cx1Potyco/maxresdefault.jpg)](https://youtu.be/J3Cx1Potyco)

**Order PCB:**  [PCBWay](https://bit.ly/2vg0xno)    

## Electronic Components
| Qty | Component | Buy |
| ------------- | ------------- | ------------- |
| 1 | UM3561 |[AliExpress](http://s.click.aliexpress.com/e/ckC9oWJA) |
| 1 | BC547 NPN Transistor |[AliExpress](http://s.click.aliexpress.com/e/bpL0Irsk) |
| 1 | 220KΩ Resistor |[AliExpress](http://s.click.aliexpress.com/e/bh4eqrQs) |
| 2 | 220Ω Resistor |[AliExpress](http://s.click.aliexpress.com/e/bh4eqrQs) |
| 1 | 5mm LED |[AliExpress](http://s.click.aliexpress.com/e/wuFpLXS) |
| 1 | SPDT Slider Switch |[AliExpress](http://s.click.aliexpress.com/e/bKFlazR2) |
| 1 | SP3T Slider Switch |[AliExpress](http://s.click.aliexpress.com/e/bZ3jBWuY) |
| 2 | 2-Pin Male Header Pins |[AliExpress](http://s.click.aliexpress.com/e/bIN5SJXw) |
| 1 | Speaker |[AliExpress](http://s.click.aliexpress.com/e/brMJh46c) |
| 1 | AA Battery Holder (2 Slot) |[AliExpress](http://s.click.aliexpress.com/e/c7Lm2Nm0) |
| 2 | AA Battery |[AliExpress](http://s.click.aliexpress.com/e/YMpokbA) |

| Tools | Buy |
|--|--|
|Soldering Iron|[AliExpress](http://s.click.aliexpress.com/e/E83bSJI) |
|Soldering Wire|[AliExpress](http://s.click.aliexpress.com/e/PdhB0nm) |

## Working
**UM3561:**

The UM3561 is a low-cost, low power CMOS LSI designed for use in toy applications. Since the integrated circuit
includes oscillating and selector circuits, a compact sound module can be constructed with only a few additional
components. The UM3561 contains a programmed mask ROM to electronically reproduce alarm sounds.

![Pinout](https://github.com/jonathanrjpereira/UM3561-Siren-Generator/blob/master/img/pinout.png)
![Pin Description](https://github.com/jonathanrjpereira/UM3561-Siren-Generator/blob/master/img/pindescription.png)

- Typical Operating Voltage = 3V
- 8-Pin DIP Package
- Power On Reset

![IC Block Diagram](https://github.com/jonathanrjpereira/UM3561-Siren-Generator/blob/master/img/ICBD.png)
![IC Truth Table](https://github.com/jonathanrjpereira/UM3561-Siren-Generator/blob/master/img/TT.png)

**Circuit:**

Only one of the Siren tunes can be played at a time. This is determined on the basis of the position of the SP3T Slide switch.
The switch has three positions which will connect the common terminal with VCC, GND or NC in order to fulfill the Truth Table.

![Block Diagram](https://github.com/jonathanrjpereira/UM3561-Siren-Generator/blob/master/img/BD.png)

A dynamic speaker is driven with an external NPN transistor.
A SPDT switch is used to turn the circuit ON & OFF.

![Schematic](https://github.com/jonathanrjpereira/UM3561-Siren-Generator/blob/master/img/sch.png)



## Contributing🛠
Are you an engineer or hobbyist who has a great idea for a new feature in this project? Maybe you have a good idea for a bug fix? Feel free to grab our code & schematics from Github and tinker with it. Don't forget to smash ⭐️ & the Pull Request button.

[![alt text][1.1]][1] [![alt text][2.1]][2] [![alt text][3.1]][3]

[1.1]: https://github.com/jonathanrjpereira/Social-Media-README/blob/master/youtube.png (YouTube)
[2.1]: https://github.com/jonathanrjpereira/Social-Media-README/blob/master/instagram.png (Instagram)
[3.1]: https://github.com/jonathanrjpereira/Social-Media-README/blob/master/github.png (GitHub)

[1]: https://www.youtube.com/channel/UCRW-41O1vy98KKgJRQoYzdg
[2]: https://www.instagram.com/electroguruji/
[3]: https://github.com/jonathanrjpereira
