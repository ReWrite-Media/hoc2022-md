### @flyoutOnly true
### @hideIteration true
### @explicitHints true


# Open Doors

## Step 1
Each one of those colored slots is a lock for a chamber door. Fill all four slots with its matching color to open the chamber doors, so we can get inside!

The included example code is broken, can you fix it? Debug the code by running it to see what it does and then edit it to the correct solution.

#### ~ tutorialhint 
Use the ``||hoc22.cursor move <direction>||`` block to move the cursor into position and then use ``||hoc22.place block||`` to fill the hole. Once all the holes are filled, the chamber doors should open.

```ghost
    hoc22.cursorMoveOrientationOneUp(1)
    hoc22.cursorMoveOrientationOneDown(1)
    hoc22.cursorMoveOrientationOneLeft(1)
    hoc22.cursorMoveOrientationOneRight(1)
    hoc22.placeMagentaBlock()
    hoc22.placeLimeBlock()
    hoc22.placeYellowBlock()
    hoc22.placeLightBlueBlock()

```
```template
    hoc22.placeLimeBlock()        
    hoc22.cursorMoveOrientationOneRight(2)
    hoc22.placeLightBlueBlock()
```

```package
minecraft-hoc22=github:ReWrite-Media/hoc22-ts
```