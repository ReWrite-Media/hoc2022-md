### @flyoutOnly true
### @hideIteration true
### @explicitHints true


# Sludge Room - Block Breaker

## Step 1
Use the cursor to break the blocks in front of the door to escape.

#### ~ tutorialhint 
Make sure you are using ``||hoc22.break block||`` to break through enough blocks. You don't have to break all of them, just enough to get to the door.



```ghost
    hoc22.cursorMoveOrientationOneUp(1)
    hoc22.cursorMoveOrientationOneDown(1)
    hoc22.cursorMoveOrientationOneLeft(1)
    hoc22.cursorMoveOrientationOneRight(1)
    hoc22.breakBlock()
    for (let index = 0; index < 2; index++) {    }
```
```template  
    hoc22.placeBlock()
    hoc22.cursorMoveOrientationOneRight(1)   
    hoc22.placeBlock()
    hoc22.cursorMoveOrientationOneRight(1)     
```
```package
minecraft-hoc22=github:ReWrite-Media/hoc22-ts#v0.2.77
```