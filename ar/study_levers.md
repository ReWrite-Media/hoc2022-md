### @flyoutOnly true
### @hideIteration true
### @explicitHints true


# Colored Levers

## Step 1
All four levers must flipped in the correct order, very quickly, to open the door. Code the Speedy Knight to rapidly pull the levers for you.

The included example code is broken, can you fix it? Debug the code by running it to see what it does and then edit it to the correct solution.

#### ~ tutorialhint 
Use the ``||hoc22.flip <color> lever||`` blocks to move the Speedy Knight to the selected color and flip the lever. Pay close attention to how many pieces of carpet there are. That will give you a clue on the order.

```ghost
    hoc22.teleportLightBlueLever()
    hoc22.teleportMagentaLever()
    hoc22.teleportYellowLever()
    hoc22.teleportOrangeLever()
```
```template
    hoc22.teleportLightBlueLever()
    hoc22.teleportOrangeLever()
    hoc22.teleportYellowLever()
    hoc22.teleportMagentaLever()
```

```package
minecraft-hoc22=github:ReWrite-Media/hoc22-ts
```