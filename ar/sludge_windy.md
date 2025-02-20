### @flyoutOnly true
### @hideIteration true
### @explicitHints true


# Windy Bridge

## Step 1
Use your cursor to block the wind, so you can walk across the bridge.

The included example code is broken, can you fix it? Debug the code by running it to see what it does and then edit it to the correct solution.

#### ~ tutorialhint 
Use the ``||hoc22.cursor move||`` blocks to position the cursor in front of the holes and then use ``||hoc22.place block||`` to fill the holes in to block the wind.



```ghost
    hoc22.cursorMoveOrientationOneUp(1)
    hoc22.cursorMoveOrientationOneDown(1)
    hoc22.cursorMoveOrientationOneLeft(1)
    hoc22.cursorMoveOrientationOneRight(1)
    hoc22.placeBlock()
```
```template
    hoc22.cursorMoveOrientationOneRight(1)   
    hoc22.placeBlock()
```
```package
minecraft-hoc22=github:ReWrite-Media/hoc22-ts
```