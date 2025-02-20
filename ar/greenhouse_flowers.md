### @flyoutOnly true
### @hideIteration true
### @explicitHints true


# Flower Planting

## Step 1
It looks like there is some type of pattern to follow in this flower bed. Maybe the planters to the left and right are clues?

The included example code is broken, can you fix it? Debug the code by running it to see what it does and then edit it to the correct solution.

#### ~ tutorialhint 
Move the cursor using the ``||hoc22.cursor move <direction>||`` block and then use ``||hoc22.place <flower>||`` to place the correct flower. Fill the entire flower bed by matching the pattern on the left and right to complete the puzzle.



```ghost
    hoc22.cursorMoveOrientationOneUp(1)
    hoc22.cursorMoveOrientationOneDown(1)
    hoc22.cursorMoveOrientationOneLeft(1)
    hoc22.cursorMoveOrientationOneRight(1)
    hoc22.flowerPlantingRedFlower()
    hoc22.flowerPlantingYellowFlower()
    hoc22.flowerPlantingBlueFlower()
    for (let index = 0; index < 2; index++) {}
```
```template
    hoc22.flowerPlantingBlueFlower() 
    hoc22.cursorMoveOrientationOneRight(3)    
    hoc22.cursorMoveOrientationOneDown(1) 
    hoc22.flowerPlantingYellowFlower()  
    hoc22.cursorMoveOrientationOneLeft(1)   
    hoc22.cursorMoveOrientationOneDown(1) 
    hoc22.flowerPlantingRedFlower()    
```
```package
minecraft-hoc22=github:ReWrite-Media/hoc22-ts
```