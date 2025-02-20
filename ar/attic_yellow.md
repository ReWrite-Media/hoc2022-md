### @flyoutOnly true
### @hideIteration true
### @explicitHints true


# Attic Tutorial

## Step 1
The Agent had just enough power to open the Green door. If you can figure out how to open the skylight, the Agent can charge up even more and open the Yellow door.

The included example code is broken, can you fix it? Debug the code by running it to see what it does and then edit it to the correct solution.

#### ~ tutorialhint 
Look above the Agent and use the ``||hoc22.cursor move||`` block to position the cursor over each trapdoor and then use ``||hoc22.open trapdoor||`` to open them. Use the colored arrows to help you choose which direction the cursor should move.



```ghost
    hoc22.cursorMoveOrientationOneUp(1)
    hoc22.cursorMoveOrientationOneDown(1)
    hoc22.cursorMoveOrientationOneLeft(1)
    hoc22.cursorMoveOrientationOneRight(1)
    hoc22.openTrapdoor()
```
```template
    hoc22.openTrapdoor()
    hoc22.cursorMoveOrientationOneRight(2)
    hoc22.cursorMoveOrientationOneUp(1)
    
```
```package
minecraft-hoc22=github:ReWrite-Media/hoc22-ts
```