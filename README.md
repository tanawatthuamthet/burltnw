# BURLSLAMTEC
[![PyPI version](https://badge.fury.io/py/burltnw.svg)](https://badge.fury.io/py/burltnw)
![test image](https://camo.githubusercontent.com/d9ff58742e2d22a28869351d857449075ef916875b1f1b5a040c8819c15be8df/68747470733a2f2f7777772e696d672e696e2e74682f696d616765732f36346136643032376532353838636632396365656233353234623063376332302e706e67)

   it is module inside of lab robotics for create application
develop by tanawat thuamthet

## Install
```
pip install burlslamtec
```

## Example
```
from burlslamtec import apollo
robot=apollo()
robot.config_ip("ip")
robot.goto(1,0)
```

## Import
```
from burlslamtec import apollo
            or
import burlslamtec
```

## Method of use

![test image](https://static.generation-robots.com/14778-product_cover/mobile-base-apollo.jpg)

### status
```
print(robot.status())
```

### battery
```
print(robot.battery())
```

### sensor
```
print(robot.sensor(1)) # degree
```

### move
```
robot.goto(1,1) # position x and position y
```

### rotate
```
robot.rotate(1) # degree
```

### home
```
robot.home()
```

### cancel
```
robot.cancel()
```
