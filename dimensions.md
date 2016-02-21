## Coils
> Wire 1.5mm; Inner Mandrel 5mm; Outer Mandrel 9mm

* Sub Gravitic 
  - 54 turns (Dia 34.394904459 @ 1.5mm dia wire and 0.5 gap) R17.19745223
  - length: 81mm (108mm with 0.5 gap)

* Gravitic Set (enlarged gap to close distance to Gravitic coils)
  - 81 turns (Dia 55.074840764 @ 1.5mm dia wire and 0.635 gap) R27.537420382 
  - Magnetic-Gravitic coil OD: 8mm
  - Magnetic-Magnetic coil OD: 12mm
  - length: 121.5mm (172.9mm with 0.639 gap)

* Magnetic Set
  - 126 turns (Dia 80.25477707 @ 1.5mm dia wire and 0.5 gap) R40.127388535
  - Gravitic-Gravitic coil OD: 8mm
  - Gravitic-Magnetic coil OD: 12mm
  - length: 189mm (252 with 0.5 gap)

## Capacitors

* Primary coil
  - 18 turns on primary (OD 8mm)
  - length: 32mm with a gap in between turns

* Feedback coil
  - 9 turns on primary (OD 8mm)
  - length: 17mm with a gap in between turns

* Battery setup (OD 5mm)
  - 1.5mm - gravitational wire
  - 2.0mm - plastic insulator
  - 0.9mm - Al GANS paper 
  - 0.6mm - Aluminium foil (circumference 13.8mm)

* Capacitor setup (OD 5mm)
  - 1.5mm - gravitational wire
  - 2.0mm - plastic insulator
  - 1.5mm - Al GANS paper 

## Health/Pain Pen

* Inner Coil: 54 Turns on 3mm mandrel
* Outer Coil: 54 Turns on 5mm mandrel
* GANS Capsule guide: 10mm (Inner Dia) x 35mm length
* GANS capsule 6mm (Inner Dia) x 25mm length

> Notes 54 turns with 0.7mm copper wire
>  (9 * 6) * (0.7 + 0.35)  
>  37.8mm (56.7mm with 0.35 gap)  

## Formula Notes

diameter of torus: (t9 * (d + g)) / pi
length of wire: (i + d/2) * pi * t

##### Where:
* t = turn constant
* d = wire diameter
* g = gap between turns
* pi = 3.14
* i = inner diamter of coiled wired

12 - 1.5 = 10.5 / 5.25
8 - 1.5 = 6.5 / 3.25

#### Coil Dimensions

##### Wire Diameter: 1.5
> Wire 1.5mm; Inner Mandrel 5.5mm; Outer Mandrel 9mm

* 126
  - ((14 * 9) * (1.5 + 0.5))/3.14 = 80.25477707 R40.127388535
  - length of wire:
    - outer grav: (5.5 + (1.5*2)) * 3.14 * 126 = 3362.94
    - outer mag: (9 + (1.5*2)) * 3.14 * 126 = 4747.68
  - length of coil:
    - 126 * 1.5 = 189
    - 126 * (1.5 + 0.5) = 252

* 81 
  - ((9 * 9) * (1.5 + 0.5))/3.14 = 51.592356688 R25.796178344
  - ((9 * 9) * (1.5 + 0.635))/3.14 = 55.074840764 R27.537420382
  - length of wire:
    - inner grav: (5.5 + (1.5*2)) * 3.14 * 81 = 2161.89
    - inner mag: (9 + (1.5*2)) * 3.14 * 81 = 3052.08
  - length of coil:
    - 81 * 1.5 = 121.5
    - 81 * (1.5 + 0.635) = 172.935

* Total length of wire: 3362.94+4747.68+2161.89+3052.08+250+252+172.935 = 13999.525
  - Power Unit: x3 = 41998.575
  - Spaceship: x12 = 167994.3


##### Wire Diameter: 1.0
> Wire 1.0mm; Inner Mandrel 3mm; Outer Mandrel 5.5mm  
> Coils OD 5mm/7.5mm

* 126
  - ((14 * 9) * (1.0 + 0.3))/3.14 = 52.165605096 R26.082802548
  - length of wire:
    - outer grav: (3 + (1.0*2)) * 3.14 * 126 = 1978.2
    - outer mag: (5.5 + (1.0*2)) * 3.14 * 126 = 2967.3   
  - length of coil:
    - 126 * 1 = 126
    - 126 * (1 + 0.3) = 163.8

* 81 
  - ((9 * 9) * (1.0 + 0.4))/3.14 = 36.114649682 R18.057324841
  - length of wire:
    - inner grav: (3 + (1.0*2)) * 3.14 * 81 = 1271.7
    - inner mag: (5.5 + (1.0*2)) * 3.14 * 81 = 1907.55
  - length of coil:
    - 81 * 1 = 81
    - 81 * (1 + 0.4) = 113.4

* Total length of wire: 1978.2+2967.3+1271.7+1907.55+200+163.8+113.4 = 8601.95
  - Power Unit: x3 = 25805.85
  - Spaceship: x12 = 103223.4
  - Spaceship single: x4 = 34407.8


## Mandrel considerations

* Wire Diameter: 1.6
  - 5.5 (8.7) - 9 (12.2)

* Wire Diameter: 1.5
  - 5.5 (8.5) - 9 (12)
 
* Wire Diameter: 1.0
  - 3 (5) - 5.5 (7.5)


## Spaceship dimensions

* [from] First reactor...
  - 2nd reactor: Forward 150mm then Left 90deg to 86.603mm
  - 3rd reactor: Forward 150mm then right 90deg to 86.603mm
  - 4th reactor: Forward 100mm then vert up to 141.014mm
  - control reactor: Forward 100mm then vert up to 70.507mm

150*2.5     = 375
86.603*2.5  = 216.5075
100*2.5     = 250
141.014*2.5 = 352.535
70.507*2.5  = 176.2675


## Stocktake

* 10 Feb 2016
  - 1.6mm 30cm  
  - 1.5mm 15m  
  - 1.0mm 29m  
  - 0.7mm 12m  



0.5 = 26.070 / H
H * 0.5 = 26
H = 26.070 / 0.5
H = 52.14

104.28


43.58+21.79=65.37
43.58+10.895=54.475

54.144 x 25.773 x 3




