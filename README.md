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
The goal of the project is to understand how an agent acts in an environment according to it perceptions.<br>
To achieve this objective the RoboDog ```agent``` and the Park ```environment``` were created.<br>
The agent must be able to interact with it perceptions and take actions.<br>
For the purpose of interactions, Food and Water ```things``` were allocated at the Park.<br>
Walk, Eat and Drink are the actions the agent is able to take.<br>
So... The RoboDog walks at the Park, notices the things that are nearby and take actions based in it perceptions.

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
