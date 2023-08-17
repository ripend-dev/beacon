# Beacon
A bot that can do anything you would ever want - now in ROBLOX. Using the built-in commands, you can automatically farm games that need grind, do tasks that are annoying, and so much more, without ever getting even suspected. Feel free to report any bugs that you have encountered while using beacon, as it is only in beta stages right now.

# USAGE
Add the loadstring into your script and execute. To try if the loadstring successfully executed, write:
```
#run debug
#goto 10, 0, 10
```
The commands above will move the player to targeted position. You can also go to a place by clicking, or by writing specifically at which part to move, for example:
```
#goto clickpos           // moves to click position
#goto mousepos           // follows and moves to the mouse position
#goto bridge/bridgePart1 // moves to a specific brick in a specific model
```
In certain games, you can move and perform an action, or even automatize it:
```
#goto ore/diamond *
#msc 1
#automatize -2
```
If we break the commands above down we'll see ```#goto ore/diamond *```, which means that the player will move to all diamond ores (the star symbolizes 'all'). The ```#msc 1``` means 'mouseclick' and first button. and lastly, ```#automatize -2``` makes the last 2 commands before self automatized, so repeating.

This README file is not yet completed and I will finish it later.
