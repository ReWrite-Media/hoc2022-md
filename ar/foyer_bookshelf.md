### @flyoutOnly true
### @hideIteration true
### @explicitHints true


# Bookcase Staircase

## Step 1
There seems to be something at the top of the bookcase. See if you can create a way to get up there.

The included example code is broken, can you fix it? Debug the code by running it to see what it does and then edit it to the correct solution.

#### ~ tutorialhint 
Move the cursor along the bookcase to select a position using the ``||hoc22.cursor move <direction>||`` block and then use ``||hoc22.place block||`` to place a block in that position. Create a staircase to get to the top.

```ghost
    hoc22.cursorMoveOrientationOneUp(1)
    hoc22.cursorMoveOrientationOneDown(1)
    hoc22.cursorMoveOrientationOneLeft(1)
    hoc22.cursorMoveOrientationOneRight(1)
    hoc22.placeBlock()
    for (let index = 0; index < 4; index++) {    }

```
```template
    hoc22.placeBlock()        
    hoc22.cursorMoveOrientationOneRight(3)
    hoc22.placeBlock()
    hoc22.cursorMoveOrientationOneRight(3)
    hoc22.placeBlock()
```

```package
minecraft-hoc22=github:ReWrite-Media/hoc22-ts
```