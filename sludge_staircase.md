### @flyoutOnly true
### @hideIteration true
### @explicitHints true


# Sludge Room - Staircase

## Step 1
Use your cursor to build a stair case!

#### ~ tutorialhint 
You need to build a staircase that you as a player can climb over. Make sure you are building at least one block at a time so you can jump over it. Try modifying the default code instead of starting from scratch.



```ghost
    hoc22.cursorMoveOrientationOneUp(1)
    hoc22.cursorMoveOrientationOneDown(1)
    hoc22.cursorMoveOrientationOneLeft(1)
    hoc22.cursorMoveOrientationOneRight(1)
    hoc22.placeBlock()
    for (let index = 0; index < 2; index++) {}
```
```template
    for (let index = 0; index < 2; index++) {
    hoc22.placeBlock()
    hoc22.cursorMoveOrientationOneUp(1)
    hoc22.cursorMoveOrientationOneRight(2)    
        }
```
```package
minecraft-hoc22=github:ReWrite-Media/hoc22-ts#v0.2.77
```