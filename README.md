# MDP REPRESENTATION

## AIM:
The MDP REPRESENTATION the robot navigate a warehouse to pick up and deliver packages.

## PROBLEM STATEMENT:
the robot must navigate a warehouse to pick up and deliver packages while avoiding obstacles and minimizing travel time.

### Problem Description
To deliver the food from pick up point 

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
 0-> current position
 1-> right
 2->left
 3-> down
 4-> up
```
### Sample Action
 0-> 3-> 3-> 1

### Reward Function
```
1.+1 for successfully reach the goal state
2. 0 for obstraction and start and pickup and reward
```

### Graphical Representation
![image](https://github.com/user-attachments/assets/0c56ec7e-bcb5-4804-bbd0-7e704503e10b)


## PYTHON REPRESENTATION:
Write your code here

## OUTPUT:
Write your Python output here

## RESULT:
Write your output here

