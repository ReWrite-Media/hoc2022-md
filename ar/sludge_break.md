### @flyoutOnly true
### @hideIteration true
### @explicitHints true


# Block Breaker

## Step 1
Use the cursor to break the blocks in front of the door to escape.

The included example code is broken, can you fix it? Debug the code by running it to see what it does and then edit it to the correct solution.

#### ~ tutorialhint 
Use the ``||hoc22.cursor move <direction>||`` block combined with ``||hoc22.break block||`` to break through enough blocks. You don't have to break all of them, just enough to get to the door.



```ghost
    hoc22.cursorMoveOrientationOneUp(1)
    hoc22.cursorMoveOrientationOneDown(1)
    hoc22.cursorMoveOrientationOneLeft(1)
    hoc22.cursorMoveOrientationOneRight(1)
    hoc22.breakBlock()
    for (let index = 0; index < 2; index++) {    }
```
```template  
    hoc22.cursorMoveOrientationOneRight(1)   
    hoc22.cursorMoveOrientationOneRight(1)     
```
```package
minecraft-hoc22=github:ReWrite-Media/hoc22-ts
```