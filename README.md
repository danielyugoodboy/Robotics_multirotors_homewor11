![image](https://github.com/Robotics-Aerial-Robots/Homework6/blob/master/Figures/LOGO%20%E4%B8%AD%E8%8B%B1%E6%96%87%E6%A9%AB.png)
# 108 年度 機器人學：多軸旋翼機 

### Homework11
Deadline: 6/2

### Topic
---
You need to finish the two parts in Homework11.

1. Please finish the update function in kalman.cpp then you can refer page 20. in the week_12 ppt.
2. Please set parameter in the kf_test.cpp and use the following dynamic model parameter.

dynamic model

<img src= "https://github.com/Robotics-Aerial-Robots/Homework11/blob/master/photo/1.png" width="40%" height="20%">	


<img src= "https://github.com/Robotics-Aerial-Robots/Homework11/blob/master/photo/2.png" height="20%">	

Suppose that the car is equipped with a position sensor that measure its position y with an additive noise v, please find the state estimate(i.e, position , velocity ,acceleration)

### real data
<img src= "https://github.com/Robotics-Aerial-Robots/Homework11/blob/master/photo/3.png" width="40%" height="20%">

### instruction
```
  roscore
  rosrun week_11 kf_test
```
