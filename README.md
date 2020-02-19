# Gear
> Quick gear calculator for engineering. If you are trying to build a gearbox, this script can be used for doing all the calculations based on values (Number of teeth, Module and The sum of rays). You can also get all info about a gear to make it on CAD.

## Features:
* Calculate the raius and diameter of a gear based on the module value.
* Calculates a second gear based on the sum of the radius set.
* Calculates the final ratio between the two gears.
* Apeends to a list the values of N OF TEETH, DIAMETER and RADIUS for both gears.
* Find an specifc ratio a the list.
* Calculates all info of a gear, such as: External diameter (de), Primitive diameter (dp), Interna diameter (di),Heith of teeth (h), Heith of head (a), Heith of feet (b) and pitch (p).

## Usage example
Set a value for the _module_ and the _sum of rays_ (in miimeters) for the gear. 
```py
modulo = 2
raysSum = 100
```
PICTURE (wait for it)
- - -
Call the function _gearByNTeeth(Number of teeth)_ .

Tip, you can change if it will print values or not, by changing:
```py
    #print('Gear1:', nTeeth_1, diameter_1, radius_1)
    #print('Gear2:', nTeeth_2, diameter_2, radius_2)
    #print('Ratio:', (radius_2 / radius_1))
```
to
```py
    print('Gear1:', nTeeth_1, diameter_1, radius_1)
    print('Gear2:', nTeeth_2, diameter_2, radius_2)
    print('Ratio:', (radius_2 / radius_1))
```

- - -
You can also make a big list of gears and find an specifc ratio
```py
for i in range(10, 101):
    gearByNTeeth(i)

findRel(2.125)
```
that will print:
```sh
Ratio: 2.125
Gear1: N of teeth: 68 Diameter: 136 Radius: 68.0
Gear2: N of teeth: 32.0 Diameter: 64.0 Radius: 32.0
```
- - -
Using the _gearByDiameter()_ method you can get all info about the gear:
```py
gearByDiameter(50)
```
that will print:
```sh
Gear: N of Teeth: 25.0 Radius: 25.0 dp: 50 Module: 2
External diameter: 54 |Primitive diameter: 50 |Interna diameter: 45.333333333333336
Heith of teeth: 4.333333333333334 |Heith of head: 2 |Heith of feet: 2.3333333333333335 |pitch: 6.283
```


## Release History
* 1.0.0
    * Script and README done
* 1.0.1
    * New method updated

## Authors

Diego Lopes Ferreira – [@Twitter](https://twitter.com/Diego45731776) – [@Instagram](https://www.instagram.com/diego.lopes.f/)

[github.com/Diego-Lopes-Ferreira](https://github.com/Diego-Lopes-Ferreira/)

