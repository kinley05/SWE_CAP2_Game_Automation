# Programming the Farming Drone (Report)
## Introduction
It is a game that can be run using a python code to farm and used for the growing of crops and unlock different varities of Entities. It is a game that will help while learning python because that has all codes of the python that we learn.


# Table of Contents
- [Code Snippets and Explanation](#code-snippets-and-explanation)
- [Challenges and Learnings](#challenges-and-learnings)
- [References](#references)
# Code-Snippets-and-Explanation
Write and explain your code along with recordings.
## Step 1: Farming on 1 tile
**Code:**
```python
while True:
if can_harvest():
    harvest()
```

**Explanation:**
The code runs an infinite number of times and harvest the grass with the if condition.

**Demo:**
Photo Demo:
![](./AFWR/Screenshot%20(111).png)

**Notes**
- Using the code above I was able to get enough hay to unlock the tile
- These features were unlocked too: variables and functions.


## Step 2: Farming on 3x3 tile
**Code:**
```python
while True:
    if can_harvest():
        harvest()
        move(North)
    move(East)
``` 


**Explanation:**
The code makes the drone go one square at a time harvests the grass with the if condition.
**Demo:**
Video Demo:
![](./AFWR/Screenshot%20(112).png)

## Step 3: Farming on 6x6 tile
**Code:**
```python
# Code to go around and farm bush
while True:
    if can_harvest():
        fore i in range(get_world_size()):
            for j in range(get_world_size()):
                move(North)
                harvest()
                plant(Entities.Bush)
                plant(Entities.Carrots)
            move(East)
```

**Explanation:**
The code makes the drone go one square at a time harvests the grass with the if condition.
**Demo:**
Video Demo:
![](./AFWR/Screenshot%20(105).png)


## Step 4: Farming on 6x6 tile
**Code:**
```python
# Code to go around and farm bush
while True:
    if can_harvest():
        for i in range(get_world_size()):
            fore j in range(get_world_size()):
                move(North)
                harvest()
                till()
                use_item(Items.Fertilizer)
                get_water()
                trade(Items.Empty_Tank)
                use_items(Itemds.Water_Tank)
                plant(Entities.Tree)
            move(East)
    else:
        move(East)
```

**Explanation:**
The code makes the drone go one square at a time harvests the grass with the if condition.
**Demo:**
Video Demo:
![](./AFWR/Screenshot%20(102).png)

## Step 5: Farming on 6x6 tile
**Code:**
```python
# Code to go around and farm bush
while True:
    if can_harvest():
        for i in range(get_world_size()):
            for j in range(get_world_size()):
                move()
                get_water()
                trade(Items.Empty)
                harvest()
             move(East)
    else:
        move(East)
```

**Explanation:**
The code makes the drone go one square at a time harvests the grass with the if condition.
**Demo:**
Video Demo:
![](./AFWR/Screenshot%20(108).png)

## Step 6: Farming on 6x6 tile
**Code:**
```python
# Code to go around and farm bush
while True:
    if can_harvest():
        for i in range(get_world_size()):
            for j in range(get_world_size()):
                move(North)
                harvest()
                till()
                trade(Items.Carrot_Seed)
                plant(Entities.Carrots)
            move(East)
    else:
        move(North)
```
**Explanation:**
The code makes the drone go one square at a time harvests the grass with the if condition.
**Demo:**
Video Demo:
![](./AFWR/Screenshot%20(104).png)

## Step 7: Farming on 6x6 tile
**Code:**
```python
# Code to go around and farm bush
while True:
    if can_harvest():
        for i in range(get_world_size()):
            for j in range(get_world_size()):
                move(North)
                harvest()
                till()
                trade(Items.Sunflower_Seed)
                plant(Entities.Sunflower)
                plant(Entities.Tree)
                move(East)
            move(East)
    else:
        move(North)
```
**Explanation:**
The code makes the drone go one square at a time harvests the grass with the if condition.
**Demo:**
Video Demo:
![](./AFWR/Screenshot%20(107).png)

## Step 8: Farming on 6x6 tile
**Code:**
```python
# Code to go around and farm bush
while True:
    if can_harvest():
        for i in range(get_world_size()):
            for j in range(get_world_size()):
                move(North)
                harvest()
                till()
                trade(Items.Water_Tank)
                plant(Item.Pumpkin_Seed)
                plant(Entities.Pumkin)
                move(East)
            move(East)
    else:
        move(North)
```
**Explanation:**
The code makes the drone go one square at a time harvests the grass with the if condition.
**Demo:**
Video Demo:
![](./AFWR/Screenshot%20(101).png)

## Step 9: Farming on 6x6 tile
**Code:**
```python
# Code to go around and farm bush
while True:
    if can_harvest():
        for i in range(get_world_size()):
            for j in range(get_world_size()):
                move(North)
                harvest()
                till()
                trade(Items.Fertilizer)
            move(East)
```
**Explanation:**
The code makes the drone go one square at a time harvests the grass with the if condition.
**Demo:**
Video Demo:
![](./AFWR/Screenshot%202024-11-02%20at%207.48.09 PM.png)



**Notes**
- Using the code above I was able to get enough hay to unlock the tile
- These features were unlocked too: variables and functions.
.
# Challenges and Learnings
## Challenges
Discuss any significant challenges you faced while trying to solve the issues in the game.
Discuss any optimization methods you implemented to make the harvesting faster.
## Learnings
Note down what different algorithms and methods of programming you learnt (E.g: Given a number n, I learnt
an algorithm that makes the drone travel each tile one by one efficiently given it’s position)
## References
List any resources, articles, or libraries you used or referenced while working on this project.
1. [Resource 1 Title](URL)
2. [Resource 2 Title](URL)
3.









