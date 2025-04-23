# MDP REPRESENTATION

## AIM:
The MDP REPRESENTATION the robot navigate a warehouse to  deliver address.

## PROBLEM STATEMENT:
The MDP representation of a robot navigating a warehouse to reach the pick-up point and deliver the package to the delivery address.
### Problem Description
To deliver the food from pick up point to delevery address

### State Space
```
 I.The robot's current position
 II.The location of the picked up.
 III. The destination where the package needs to be delivered.
 IV.The positions of obstacles in the warehouse.
```
 

 

### Sample State
```
1.The robot is at 1 position
2.The package to be picked up is at 3 position.
3. The delivery point is at 6 position.
4. Obstacles are at positions 2 and 4 position.
```

### Action Space
```
0    ->>  Same State
1    ->> Left
2    ->> Down
3    ->> Right
4    ->> Up
```
### Sample Action
 0-> 3-> 3-> 1

### Reward Function
```
1.+1 for successfully reach the goal state
2. 0 for obstraction and start and pickup and reward
```

### Graphical Representation

![WhatsApp Image 2025-04-23 at 11 27 52_c2349466](https://github.com/user-attachments/assets/2726df17-fa19-4748-b1a9-315f221df897)


## PYTHON REPRESENTATION:
```
p={
    1:{
    0:[(1,0,0,False)],
    1:[(1,0,0,False)],
    2:[(0.7,3,0,True),(0.3,2,0,False)],
    3:[(0.3,2,0,False),(0.7,3,0,True)],
    4:[(1,0,0,False)]},
    2:{
       0:[(1,2,0,True)],
       1:[(1,2,0,True)],
       2:[(1,2,0,True)],
       3:[(1,2,0,True)],
       4:[(1,2,0,True)]}, 
    3:{
       0:[(1,3,0,False)],
       1:[(1,3,0,False)],
       2:[(1,3,0,False)],
       3:[(0.98,4,1,True),(0.7,1,0,False)],
       4:[(0.7,1,0,False),(0.98,4,1,True)]}, 
    4:{
       0:[(1,4,0,True)],
       1:[(1,4,0,True)],
       2:[(1,4,0,True)],
       3:[(1,4,0,True)],
       4:[(1,4,0,True)]}   
}

```


## OUTPUT:
![image](https://github.com/user-attachments/assets/7c7e7d2d-2e8a-4a12-b67b-39d8aa6f81c3)


## RESULT:
Thus, The MDP Represntation of reaching a deliver address from warehous while avoiding 
 obstacles and minimizing travel time is successfully executed.

