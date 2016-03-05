## Coils
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

523.24 * 6.4 = 3348.7  
523.24 * 9.0 = 4709.2  


* 81 
  - ((9 * 9) * (1.5 + 0.5))/3.14 = 51.592356688 R25.796178344
  - ((9 * 9) * (1.5 + 0.635))/3.14 = 55.074840764 R27.537420382
  - length of wire:
    - inner grav: (5.5 + (1.5*2)) * 3.14 * 81 = 2161.89
    - inner mag: (9 + (1.5*2)) * 3.14 * 81 = 3052.08
  - length of coil:
    - 81 * 1.5 = 121.5
    - 81 * (1.5 + 0.635) = 172.935

523.24 * 4.1 = 2145.3  
523.24 * 5.8 = 3034.8  

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

523.24 * 3.8 = 1988.3  
523.24 * 5.7 = 2982.5  

* 81 
  - ((9 * 9) * (1.0 + 0.4))/3.14 = 36.114649682 R18.057324841
  - length of wire:
    - inner grav: (3 + (1.0*2)) * 3.14 * 81 = 1271.7
    - inner mag: (5.5 + (1.0*2)) * 3.14 * 81 = 1907.55
  - length of coil:
    - 81 * 1 = 81
    - 81 * (1 + 0.4) = 113.4

523.24 * 2.4 = 1255.8  
523.24 * 3.6 = 1883.7  

* Total length of wire: 1978.2+2967.3+1271.7+1907.55+200+163.8+113.4 = 8601.95
  - Power Unit: x3 = 25805.85
  - Spaceship: x12 = 103223.4
  - Spaceship single: x4 = 34407.8

* spacing: 54.172

## Cores



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

### Plasma Capacitor 8

#### Length of coil:
* 27 * (1.5 + 0.7) = 59.4

#### Length of wire:
* Mag coiled: ((5 + 1.5) * 3.14) * 27 = 551.07
* Mag connections: 62.1 + 5 + 30 = 97.1
* Total: 551.07+97.1 = 648.17
* Grav: 62.1 + 5 + 62.1 + 5 + 30 = 164.2

#### Dimensions:
* loop-back: 70
* Mag: 733
* Grav: 209 (70 + 10 + 70 + 10 + 20 + 29 = 209)
* capacitor paper: 65 x 282
* battery paper: 65 x 190
* aluminium: 60 x 15
* sleave: 70

#### Notes
* 523.24 * .35 = 209
* 523.24 * 1.4 = 733




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

## Mandrel considerations

* Wire Diameter: 1.6
  - 5.5 (8.7) - 9 (12.2)

* Wire Diameter: 1.5
  - 5.5 (8.5) - 9 (12)
 
* Wire Diameter: 1.0
  - 3 (5) - 5.5 (7.5)


## Spaceship core reactor positioning

* Tetrahedron layout: from 1st reactor...
  - 2nd reactor: Forward 150mm then Left 90deg to 86.603 (H=173.20531)
  - 3rd reactor: Forward 150mm then right 90deg to 86.603 (H=173.20531)
  - 4th reactor: Forward 100mm then vertical 90deg to 141.42164 (H=173.20531)
  - central position: Forward 100mm then vertical 90deg to 35.711
* Cores: 30 x 52
* Gravitational cores radius: 100
* Gravitational coil radius: 55.83247 (coil length 350.6279116 with gap)
  - 175 turns and 4126.5mm of wire (1.5 and 0.5 gap)
* Magnetical cores radius: 188.33506
* Magnetical coil radius: 144.16753 (coil length 905.3720884 with gap)
  - 453 turns 10668.15mm of wire (1.5 and 0.5 gap)
  - 604 turns 

## Circumference at a Given Latitude
* 2 x pi x r x cos(L)

##### Where: 
* r = radius of sphere
* L = Latitude
* pi = 3.1415926535897



