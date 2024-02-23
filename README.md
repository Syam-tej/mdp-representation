# MDP REPRESENTATION

## AIM:
To represent a Markov Decision Process(MDP) problem in the following ways.

1.Text representation

2.Graphical representation

3.Python - Dictonary representation

## PROBLEM STATEMENT:
```
DEVELOPED BY : P SYAM TEJ
REF NO : 212221240056
```
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
![grapical](https://github.com/Syam-tej/mdp-representation/assets/93427224/c3d34a48-e98c-4e15-b57a-42ef3e67857b)

## PYTHON REPRESENTATION:
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
![image](https://github.com/Sandhyacharu/mdp-representation/assets/75235167/2c94eeb9-7731-4901-b5a4-c78a27ff4c19)

## RESULT:
Thus, an environment to check whether the child plays or stay at home is created according to the weather conditions.
