![](https://github.com/slim-gears/sg-bot/raw/master/docs/img/sgbot-render-2.png)

# SG-Bot

## Work is still in progress...

## Fully enclosed Core XY 3d printer with replaceable head

### SG-Bot main features
- Fully enclosed
- Replaceable heads
- Built-in piezo leveling sensor
- Affordable and highly available parts

### Fully enclosed
Fully enclosed design, with acrylic (plexiglass) walls and top

<img src="https://github.com/slim-gears/sg-bot/raw/master/docs/img/sgbot-render-1.png" height="240px">

### Repleacable head
Easily detachable head, allowing to use various heads:
- [x]  Bowden head 
- [x]  Pen holder head
- [ ]  Remote shaft direct extruder head - *to be designed*
- [ ]  Multimaterial head - *to be designed*
- [ ]  Laser Engraver head - *to be designed*
- [ ]  Custom head

<img src="https://github.com/slim-gears/sg-bot/raw/master/docs/img/sgbot-render-carriage-2.png" height="240px"> <img src="https://github.com/slim-gears/sg-bot/raw/master/docs/img/sgbot-render-head-2.png" height="240px">

### Built-in piezo leveling sensor

#### Built-in
One of the primary design goals was to have a replaceable head. In order to avoid the need for each head to have its own leveling sensor, it was decided to have a leveling sensor as part of the carriage

#### Piezo sensor
Multiple sensor options were tried before designing piezo sensor:
- Optical IR differential sensor
- Capacitive sensor (LGC12A3)
- Inductive sensor

These sensors were tried with different build surfaces (Flexible magnetic surface, Spring Sheet surface, Borosilicate glass, Plain glass, etc.). All these options could not provide consistent results when changing heads and surfaces. So I designed a carriage with single 20mm piezo disc based sensor. It showed pretty good results, but sometimes had repeatability issues. Since overall the piezo approach seemed very promissing I tried to approve the design to use 5 12mm piezo discs. Now it shows pretty consistent results.

<img src="https://github.com/slim-gears/sg-bot/raw/master/docs/img/sgbot-render-carriage-sensors-2.png" height="240px"> <img src="https://github.com/slim-gears/sg-bot/raw/master/docs/img/sgbot-render-carriage-sensors-1.png" height="240px">
