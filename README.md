<p align="right">
  <a>
    <img src="https://cdn-icons-png.flaticon.com/512/3909/3909219.png" width="14" height="14">
    <a href="link"> DE</a>
    <br>
    <img src="https://cdn-icons-png.flaticon.com/512/3909/3909370.png" width="14" height="14">
    <a href="link"> PT-BR</a>
  </a>
</p>

<p align="center">
  <a>
    <img src="https://external-preview.redd.it/89YLIhzlwSzVHq9ZKIgD4ySf8JHmQThqS9oJGCdo73w.jpg?auto=webp&s=a04778fdb64d396eec7800f18e0b97e6011a2df5" width="308" height="226">
  </a>
</p>

<h3 align="center">Hunt the Wumpus</h3>

<p align="center">
  This is a personal project for AI studies.
</p>

## Introduction
"Hunt the Wumpus" is a game in which the player need to get the ```treasure``` out of the ```cave```.<br>
The cave ```environment``` is a 4x4 grid that provides some perceptions to the player.<br>
And they are: ```Breeze```, ```Stentch``` and ```Glow```.<br>
Player starts in position ```[0,0]```.<br>
Wumpus ```monster``` and pits are randomly allocated in cave.<br>
The objective is to reach the treasure while avoid dying based on its perceptions.<br>


## Technologies
Project is created with:
* Python: 3.9.12

## Features
```knowledge.py```<br />
...

```entity.py```<br />
...

```enumeration.py```<br />
...

```movement.py```<br />
...

```game.py```<br />
...

## Output
First output we get when we run ```game.py```:

``` Ruby
Agent
Location: (0, 0)
Direction: East
Is there gold? False
Is there arrow? True

# |_X_||___||___||___|
# |___||___||___||___|
# |___||___||___||___|
# |___||___||___||___|

No perceptions.

# 1) Move foward
# 2) Turn left
# 3) Turn right
# 4) Grab
# 5) Shoot

What's your next action?
