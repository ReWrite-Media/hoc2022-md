### @flyoutOnly true
### @hideIteration true
### @explicitHints true


# Cracked Wall

## Step 1
The garden needs more water! Use the cursor to break some of these damaged bricks to get more water flowing.

The included example code is broken, can you fix it? Debug the code by running it to see what it does and then edit it to the correct solution.

#### ~ tutorialhint 
Move the cursor using the ``||hoc22.cursor move <direction>||`` block and then use ``||hoc22.break block||`` to break a block in that position. Break all 4 blocks to get enough water to get to the next puzzle. 



```ghost
    hoc22.cursorMoveOrientationOneUp(1)
    hoc22.cursorMoveOrientationOneDown(1)
    hoc22.cursorMoveOrientationOneLeft(1)
    hoc22.cursorMoveOrientationOneRight(1)
    hoc22.breakBlock()
```
```template
    hoc22.cursorMoveOrientationOneDown(1) 
    hoc22.breakBlock()
    hoc22.cursorMoveOrientationOneRight(4) 
    hoc22.breakBlock() 
    hoc22.cursorMoveOrientationOneDown(4)
    hoc22.cursorMoveOrientationOneLeft(1)
    hoc22.breakBlock()
```
```package
minecraft-hoc22=github:ReWrite-Media/hoc22-ts
```