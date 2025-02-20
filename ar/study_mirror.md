### @flyoutOnly true
### @hideIteration true
### @explicitHints true


# Wrong Reflection

## Step 1
The pumpkins above the fireplace in the mirror is somehow different than the ones in this room. Try making them match.

The included example code is broken, can you fix it? Debug the code by running it to see what it does and then edit it to the correct solution.

#### ~ tutorialhint 
Move the cursor above the fireplace using ``||hoc22.cursor move <direction>||`` to select a position and ``||hoc22.place pumpkin||`` to place a pumpkin in that position.

```ghost
    hoc22.cursorMoveOrientationOneUp(1)
    hoc22.cursorMoveOrientationOneDown(1)
    hoc22.cursorMoveOrientationOneLeft(1)
    hoc22.cursorMoveOrientationOneRight(1)
    hoc22.placePumpkin()
    for (let index = 0; index < 2; index++) {}

```
```template
    hoc22.cursorMoveOrientationOneLeft(1)
    hoc22.placePumpkin()
    hoc22.cursorMoveOrientationOneLeft(1)
    hoc22.placePumpkin()
    hoc22.cursorMoveOrientationOneLeft(1)
    hoc22.placePumpkin()
    hoc22.cursorMoveOrientationOneLeft(1)
```

```package
minecraft-hoc22=github:ReWrite-Media/hoc22-ts
```