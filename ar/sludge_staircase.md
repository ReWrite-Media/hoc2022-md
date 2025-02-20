### @flyoutOnly true
### @hideIteration true
### @explicitHints true


# Staircase

## Step 1
Use your cursor to build a staircase to access the upper level!

The included example code is broken, can you fix it? Debug the code by running it to see what it does and then edit it to the correct solution.

#### ~ tutorialhint 
Use the ``||hoc22.move cursor <direction>||`` and ``||hoc22.place block||`` blocks to build a staircase that you as a player can climb over. Make sure you are building at least one block at a time so you can jump over it. Try modifying the default code instead of starting from scratch.



```ghost
    hoc22.cursorMoveOrientationOneUp(1)
    hoc22.cursorMoveOrientationOneDown(1)
    hoc22.cursorMoveOrientationOneLeft(1)
    hoc22.cursorMoveOrientationOneRight(1)
    hoc22.placeBlock()
    for (let index = 0; index < 2; index++) {}
```
```template
    hoc22.placeBlock()
    hoc22.cursorMoveOrientationOneRight(2)   
    hoc22.placeBlock() 
```
```package
minecraft-hoc22=github:ReWrite-Media/hoc22-ts
```