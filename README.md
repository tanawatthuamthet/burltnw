# BURL Tnw
[![Version](https://badge.fury.io/gh/tterb%2FHyde.svg)](https://github.com/tanawatthuamthet)
![test image](https://www.img.in.th/images/874c0d89c594b276dab9cbf223465ec0.png)

## Install
```
pip install burltnw
```

## Method of use
### status
```
import burltnw
robot = burltnw.apollo()
print(robot.get_status())
```

### battery
```
import burltnw
robot = burltnw.apollo()
print(robot.get_battery())
```

### move
```
import burltnw
robot = burltnw.apollo()
print(robot.walk(1,1)) # position x and position y
```

### rotate
```
import burltnw
robot = burltnw.apollo()
print(robot.rotate(1)) # degree
```

### home
```
import burltnw
robot = burltnw.apollo()
print(robot.home())
```
