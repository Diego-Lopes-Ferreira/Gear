# Gear
> Quick gear calculator for engineering. If you are trying to build a gearbox, this script can be used for doing all the calculations based on values (Number of teeth, Module and The sum of rays)

## Features:
* Calculate the raius and diameter of a gear based on the module value.
* Calculates a second gear based on the sum of the radius set.
* Calculates the final ratio between the two gears.
* Apeends to a list the values of N OF TEETH, DIAMETER and RADIUS for both gears.
* Find an specifc ratio a the list

## Usage example
Set a value for the _module_ and the _sum of rays_ (in miimeters) for the gear. 
```py
modulo = 2
raysSum = 100
```

PICTURE (wait for it)

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


You can also make a big list of gears and find an specifc ratio
```py
for i in range(10, 101):
    gearByNTeeth(i)

findRel(2.125)
```
that will print
```sh
Ratio: 2.125
Gear1: N of teeth: 68 Diameter: 136 Radius: 68.0
Gear2: N of teeth: 32.0 Diameter: 64.0 Radius: 32.0
```

## Release History
* 1.0
    * Script and README done

## Me

Diego Lopes Ferreira – [@Twitter](https://twitter.com/Diego45731776) – [@Instagram](https://www.instagram.com/diego.lopes.f/)

[github.com/Diego-Lopes-Ferreira](https://github.com/Diego-Lopes-Ferreira/)

