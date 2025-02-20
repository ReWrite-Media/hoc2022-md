### @flyoutOnly true
### @hideIteration true
### @explicitHints true


# Laser Reveal

## Step 1
Fill in all the holes in the floor with the cursor to open the red curtain.

The included example code is broken, can you fix it? Debug the code by running it to see what it does and then edit it to the correct solution.

#### ~ tutorialhint 
Fill all the holes in the floor by using the ``||hoc22.cursor move||`` block to position the cursor and ``||hoc22.place block||`` to fill in the holes.



```ghost
    hoc22.cursorMoveOrientationOneUp(1)
    hoc22.cursorMoveOrientationOneDown(1)
    hoc22.cursorMoveOrientationOneLeft(1)
    hoc22.cursorMoveOrientationOneRight(1)
    hoc22.placeBlock()
```
```template  
    hoc22.placeBlock()
    hoc22.cursorMoveOrientationOneUp(3)       
    hoc22.placeBlock() 
    hoc22.cursorMoveOrientationOneRight(5)
```
```package
minecraft-hoc22=github:ReWrite-Media/hoc22-ts
```