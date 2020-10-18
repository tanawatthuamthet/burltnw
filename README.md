# BURL Tnw
[![Version](https://badge.fury.io/gh/tterb%2FHyde.svg)](https://github.com/tanawatthuamthet)
![test image](https://www.img.in.th/images/874c0d89c594b276dab9cbf223465ec0.png)

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
