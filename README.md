# MDP REPRESENTATION

## AIM:
To represent a Markov Decision Process(MDP) problem in the following ways.

1.Text representation

2.Graphical representation

3.Python - Dictonary representation

## PROBLEM STATEMENT:
### Problem Description
An agent needs to pick product B from a supermarket where there are three products A , B and C

### State Space
{Product A , Product B , Product C}

### Sample State
Product A

### Action Space
[Left , Right , Pick}

### Sample Action
Left

### Reward Function
+1 - when an agent move to the right side and pick product B
0 - Otherwise

### Graphical Representation
![graphical](https://github.com/Syam-tej/mdp-representation/assets/93427224/944b2366-fe04-41e3-b974-a05724c3e37e)

## PYTHON REPRESENTATION:
```
Developed By: P Syam Tej
Reg. No: 212221240056
```
```python3
P = {
    0:{
        0: [(1.0,0,0.0,True)],
        1: [(1.0,0,0.0,True)]
    },
    1:{
        0: [(1.0,0,0.0,True)],
        1: [(1.0,2,1.0,True)]
    },
    2:{
        0: [(1.0,2,0.0,True)],
        1: [(1.0,2,0.0,True)]
    }
}
```
## OUTPUT:
![output](https://github.com/Syam-tej/mdp-representation/assets/93427224/05b3cc56-c3ce-459a-913e-8cc6033b5a35)

## RESULT:
Thus, an environment to check whether the child plays or stay at home is created according to the weather conditions.
