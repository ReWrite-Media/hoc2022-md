### @flyoutOnly true
### @hideIteration true
### @explicitHints true


# Vent

## Step 1
Move the clay ball through the vent in order to reach the next section.

#### ~ tutorialhint 
Use the ``||hoc22.clay ball move <direction> by <number>||`` block to move the clay ball through the vent.



```ghost
    hoc22.clayBallMove(FourDirectionUpDown.Up, 1)
```
```template
    hoc22.clayBallMove(FourDirectionUpDown.Right, 2)  
    hoc22.clayBallMove(FourDirectionUpDown.Left, 2)     
```
```package
minecraft-hoc22=github:ReWrite-Media/hoc22-ts#v0.3.41
```