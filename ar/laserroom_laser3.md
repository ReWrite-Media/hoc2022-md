### @flyoutOnly true
### @hideIteration true
### @explicitHints true


# Laser Puzzle

## Step 1
Solid blocks stop the laser! Shift all 3 rows on the floor to make the laser pass-through the glass blocks and turn on the light at the other side.

The included example code is broken, can you fix it? Debug the code by running it to see what it does and then edit it to the correct solution.

#### ~ tutorialhint 
Use the ``||hoc22.shift||`` blocks to select which row you want to move, and the direction it should move in. The block at the end of the row you are shifting will get bumped to the other side.



```ghost
    hoc22.GreenLeftLaser(1)
    hoc22.GreenRightLaser(1)
    hoc22.YellowLeftLaser(1)
    hoc22.YellowRightLaser(1)
    hoc22.RedLeftLaser(1)
    hoc22.RedRightLaser(1)    
```
```template
    hoc22.GreenLeftLaser(1)
    hoc22.YellowLeftLaser(1)
    hoc22.RedLeftLaser(3)
      
```
```package
minecraft-hoc22=github:ReWrite-Media/hoc22-ts
```