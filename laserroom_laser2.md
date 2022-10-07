### @flyoutOnly true
### @hideIteration true
### @explicitHints true


# Laser Puzzle

## Step 1
Solid blocks stop the lasers! Shift the green and yellow rows on the floor to make the laser pass through the Glass blocks and power on the light at the other side. 

#### ~ tutorialhint 
Use the ``||hoc22.shift||`` blocks to select which row you want to move, and the direction it should move in. The block at the end of the row you are shifting will get bumped to the other side.



```ghost
    hoc22.GreenLeftLaser(1)
    hoc22.GreenRightLaser(1)
    hoc22.YellowLeftLaser(1)
    hoc22.YellowRightLaser(1)
```
```template
    hoc22.GreenLeftLaser(1)
    hoc22.YellowLeftLaser(1)
      
```
```package
minecraft-hoc22=github:ReWrite-Media/hoc22-ts#v0.3.41
```