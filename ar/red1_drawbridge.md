### @flyoutOnly true
### @hideIteration true
### @explicitHints true


# Drawbridge

## Step 1
The Enderman butler needs help getting across the river. Teleport the butler across the river to the Diamond block. Then move the butler to the lever and pull it down.

The included example code is broken, can you fix it? Debug the code by running it to see what it does and then edit it to the correct solution.

#### ~ tutorialhint 
Teleport the Enderman butler to the Diamond block by using the ``||hoc22.teleport enderman||`` block. Then use the ``||hoc22.move enderman||`` block to position them and ``||hoc22.pull lever down||`` to flip the lever. The Enderman will automatically turn to face the lever when you use the ``||hoc22.pull lever down||`` block.



```ghost
    hoc22.endermanButlerMoveForward(1)
    hoc22.superJump()
    hoc22.pullLeverDown()
```
```template
    hoc22.endermanButlerMoveForward(2)
    hoc22.superJump()
    hoc22.endermanButlerMoveForward(2)
    hoc22.pullLeverDown()  
```
```package
minecraft-hoc22=github:ReWrite-Media/hoc22-ts
```