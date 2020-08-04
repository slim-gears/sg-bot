# SG-Bot (*Work in progress*)

![](https://github.com/slim-gears/sg-bot/raw/master/docs/img/sgbot-render-2.png)

- [Credits](#credits)
- [Main features](#main-features)
- [Source model](#source-model)

## Credits
- Although the project was fully design from scratch, the design was highly inspired by [BLV-MGN-Cube](https://www.blvprojects.com/blv-mgn-cube-3d-printer) (thanks to [Ben Levi](https://www.blvprojects.com/about) and BLV MGN community for various ideas, taken into SG-bot)
- The project uses various standard parts models taken from [GrabCad library](https://grabcad.com/library)
- The project was designed using Fusion 360 community edition

## Fully enclosed Core XY 3d printer with replaceable head

### Main features
- [Fully enclosed](#fully-enclosed)
- [CoreXY kinematics](#corexy-kinematics)
- [Replaceable heads](#replaceable-heads)
- [Carriage-mounted leveling sensor](#built-in-leveling-sensor)
- [Affordable and widely available parts](#affordable-and-widely-available-parts)

### Fully enclosed
Fully enclosed design, with acrylic (plexiglass) walls and top

<img src="https://github.com/slim-gears/sg-bot/raw/master/docs/img/sgbot-render-1.png" height="240px">

### CoreXY kinematics
Core XY kinematics was chosen for space efficiency

<img src="https://github.com/slim-gears/sg-bot/raw/master/docs/img/sgbot-render-kinematics-1.png" height="120px"> <img src="https://github.com/slim-gears/sg-bot/raw/master/docs/img/sgbot-render-kinematics-2.png" height="120px">

### Replaceable heads
Easily detachable head, allowing to use various heads:
- [x]  Bowden head 
- [x]  Pen holder head
- [ ]  Remote shaft direct extruder head - *to be designed*
- [ ]  Multimaterial head - *to be designed*
- [ ]  Laser Engraver head - *to be designed*
- [ ]  Custom head

<img src="https://github.com/slim-gears/sg-bot/raw/master/docs/img/sgbot-render-carriage-2.png" height="240px"> <img src="https://github.com/slim-gears/sg-bot/raw/master/docs/img/sgbot-render-head-2.png" height="240px">

### Built-in leveling sensor

#### Built-in
One of the primary design goals was to have a replaceable head. In order to avoid the need for each head to have its own leveling sensor, it was decided to have a leveling sensor as part of the carriage and not part of the head

#### Piezo sensor
Multiple sensor options were tried before designing piezo sensor:
- Optical IR differential sensor
- Capacitive sensor (LGC12A3)
- Inductive sensor

These sensors were tried with different build surfaces (Flexible magnetic surface, Spring Sheet surface, Borosilicate glass, Plain glass, etc.). All these options could not provide consistent results when changing heads and surfaces. So I designed a carriage with single 20mm piezo disc based sensor. It showed pretty good results, but sometimes had repeatability issues. Since overall the piezo approach seemed very promissing I tried to approve the design to use 5 12mm piezo discs. Now it shows pretty consistent results.

<img src="https://github.com/slim-gears/sg-bot/raw/master/docs/img/sgbot-render-carriage-sensors-2.png" height="240px"> <img src="https://github.com/slim-gears/sg-bot/raw/master/docs/img/sgbot-render-carriage-sensors-1.png" height="240px">

### Affordable and widely available parts
- Standard T-Slot 2040 and 2020 alluminium extrusion profiles
- Hiwin MGN12 rails
- SKR Pro 1.1 board

### Source model
Source model is available [here](https://a360.co/39YiT02)
