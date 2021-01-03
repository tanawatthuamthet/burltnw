# BURL Tnw
[![PyPI version](https://badge.fury.io/py/burltnw.svg)](https://badge.fury.io/py/burltnw)
![test image](https://camo.githubusercontent.com/d9ff58742e2d22a28869351d857449075ef916875b1f1b5a040c8819c15be8df/68747470733a2f2f7777772e696d672e696e2e74682f696d616765732f36346136643032376532353838636632396365656233353234623063376332302e706e67)

   it is module inside of lab robotics for create application
created by tanawat thuamthet

## Install
```
pip install burltnw
```

## Import
```
import burltnw
```

## Method of use

![test image](https://static.generation-robots.com/14778-product_cover/mobile-base-apollo.jpg)

### status
```
robot = burltnw.apollo()
print(robot.get_status())
```

### battery
```
robot = burltnw.apollo()
print(robot.get_battery())
```

### move
```
robot = burltnw.apollo()
print(robot.walk(1,1)) # position x and position y
```

### rotate
```
robot = burltnw.apollo()
print(robot.rotate(1)) # degree
```

### home
```
robot = burltnw.apollo()
print(robot.home())
```
