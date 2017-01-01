## Formulae
* Diameter of Torus = (Number of windngs * (Wire Diameter + Winding gap)) / Pi
* Length of wire required = (Mandrel Diameter + (Wire Diameter * 2)) * Pi * Number of Windings
* Circumferense of Torus = Number of windings * (Wire Diameter + Winding gap)

## Specifications

### Coil 
* Wire Diameter: 1.626mm

* Outer Mandrel diameter: 9mm

* Inner Mandrel diameter: 5.5mm

* Outer Torus: 135 windings
  - (135 * (1.626 + 0.8))/3.14 = 104.302547771 R52.151273886
  - length of wire:
    - outer grav: (5.5 + (1.626*2)) * 3.14 * 135 = 3709.9728
    - outer mag: (9 + (1.626*2)) * 3.14 * 135 = 5193.6228
  - length of coil:
    - 135 * 1.626 = 219.51
    - 135 * (1.626 + 0.8) = 327.51

* Inner Torus - 99 windings
  - (99 * (1.626 + 0.8))/3.14 = 76.488535032 R38.244267516
  - length of wire:
    - outer grav: (5.5 + (1.626*2)) * 3.14 * 99 = 2720.64672
    - outer mag: (9 + (1.626*2)) * 3.14 * 99 = 3808.65672
  - length of coil:
    - 99 * 1.626 = 160.974
    - 99 * (1.626 + 0.8) = 240.174

### Capacitor 
* Wire Diameter: 1.5mm

* Outer Mandrel diameter: 7mm

* Inner Mandrel diameter: 3mm

* Outer cylinder: 18 windings
  - Anode connecter length: 20mm

* Inner cylinder: 18 windings
  - Cathode connector length: 20mm

### Capacitor plug 

* Wire Diameter: 1.0mm

* 15 windings


### 3D drawing  

* Main Torus 
  - 1.626 * 2 + 9 = 12.252 R6.126
  - coil: 6.126 / 12.252
  - cutaway: 6.4 / 12.8
  - molding: 8.4 / 16.8

* Coil-tray
  - Outer: R61.55
  - Inner: R28.84

* Notes
  - 52/1.55 = 33.5484
  - (1.5 + (1.55*2)) * 3.14 * 33.5 = 483.874
