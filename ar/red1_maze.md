### @flyoutOnly true
### @hideIteration true
### @explicitHints true


# Maze

## Step 1
The Enderman butler needs your help getting through the maze to the Emerald blocks on the other side. The levers on the wall seem to match the doors colors. When flipping the lever, one door opens and another closes. 

The included example code is broken, can you fix it? Debug the code by running it to see what it does and then edit it to the correct solution.

#### ~ tutorialhint 
Create a path to the Emerald blocks by using the levers. Be careful! Opening one door will close the other. Then, use the ``||hoc22.move enderman||`` blocks to get them through the maze to the emerald blocks.



```ghost
    hoc22.npcMoveForward(1)
    hoc22.npcMoveBack(1)
    hoc22.npcMoveLeft(1)
    hoc22.npcMoveRight(1)
```
```template
    hoc22.npcMoveForward(2)
    hoc22.npcMoveRight(3) 
```
```package
minecraft-hoc22=github:ReWrite-Media/hoc22-ts
```