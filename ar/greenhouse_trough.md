### @flyoutOnly true
### @hideIteration true
### @explicitHints true


# Trough

## Step 1
Oh no! It looks like the water isn't reaching the garden. Fill in all the holes so the water can flow correctly.

The included example code is broken, can you fix it? Debug the code by running it to see what it does and then edit it to the correct solution.

#### ~ tutorialhint 
Move the cusor using the ``||hoc22.cursor move <direction>||`` block and then use ``||hoc22.place block||`` to place a block in that position. Fill in all 6 holes that are above the black concrete to continue.



```ghost
    hoc22.cursorMoveOrientationOneUp(1)
    hoc22.cursorMoveOrientationOneDown(1)
    hoc22.cursorMoveOrientationOneLeft(1)
    hoc22.cursorMoveOrientationOneRight(1)
    hoc22.placeBlock()
    for (let index = 0; index < 2; index++) {    }
```
```template
    hoc22.cursorMoveOrientationOneUp(1) 
    hoc22.placeBlock()   
    hoc22.cursorMoveOrientationOneUp(1) 
    hoc22.placeBlock()        
    hoc22.cursorMoveOrientationOneRight(2)   
    hoc22.cursorMoveOrientationOneUp(1) 
    hoc22.placeBlock()       
```
```package
minecraft-hoc22=github:ReWrite-Media/hoc22-ts
```