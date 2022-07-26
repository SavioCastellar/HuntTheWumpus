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
* Python: 3.6.0
* Notebook: 4.3.1

<a href="https://github.com/SavioCastellar/RoboDog/blob/main/requirements.txt">Requirements</a>

## Features
```agents.py```<br />
File where the agent, the enviroment and those attributes are defined.
```agents.ipynb```<br />
You can run the program in a Jupyter Notebook from here.
```agents.yaml```<br />
That's the python env.
```AIBO.jpg```<br />
RoboDog image ^.^
```requirements.txt```<br />
The version for all used packages can be seen here.
## Output
Setting up the environment:

``` Ruby
    # RoboDog at position 0
    park.add_thing(dog, 0)
    
    # Food at position 5
    park.add_thing(food, 5)
    
    # Water at position 7
    park.add_thing(water, 7)
    
    # Number of steps
    park.run(10)
```

For the environment above, that's the output we get:

``` Ruby
    [<RoboDog>]
    [<RoboDog>]
    [<RoboDog>]
    [<RoboDog>]
    [<RoboDog>]
    [<RoboDog>, <Food>]
    RoboDog: Ate at 5.
    [<RoboDog>]
    [<RoboDog>]
    [<RoboDog>, <Water>]
    RoboDog: Drank at 7.
```
