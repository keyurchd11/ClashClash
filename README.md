# ClashClash

A terminal-based version of Clash Of Clans using Python and OOPs principles.

<p align="center">
    <img src="gameplay.gif" width="512"/>
</p>

## Object-Oriented Programming

Python Game

Gameplay:

The game starts with the user selecting which hero he/she wants to use (King or Queen)

Keys:

Spawning at spawn point 1:

z: Barbarians

1: Hero

v: Archers

4: Balloons

Spawning at spawn point 2:

x: Barbarians

2: Hero

b: Archers

5: Balloons

Spawning at spawn point 3:

c: Barbarians

3: Hero

n: Archers

6: Balloons

Controlling the movement of Hero:

w: up

a: left

s: down

d: right

Spells:

r: rage spell

h: heal spell

Attacking using King:

i: attack up

j: attack left
k: attack down

l: attack right

Attacking using Queen:

[space]: normal attack

m: Archer Queen’s eagle arrow

### OOPs concepts used:

- Inheritance: Generic classes for game objects and all the
objects inheriting these classes. Basic character and building classes are inherited by all other classes specific to different types of game objects.
- Polymorphism: Multiple functions with the same name but a varying number of arguments used.
- Encapsulation: Class and object-based approach for all the functionality implemented.
- Abstraction: Intuitive functionality like move(), attack(), etc, showing away inner details from the end user.