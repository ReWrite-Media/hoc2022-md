### @flyoutOnly true
### @hideIteration true
### @explicitHints true


# Pitfall

## Step 1
Move the clay golem forward 6 blocks. When the golem steps on a pressure plate, it will open a pit for 1 second. Make it wait for the block to come back before moving forward.

The included example code is broken, can you fix it? Debug the code by running it to see what it does and then edit it to the correct solution.

#### ~ tutorialhint 
Move the golem forward by using the ``||hoc22.move golem forward by <number>||`` block. Move the golem forward 2 blocks and then use ``||hoc22.wait for block||`` to have the golem wait 1 second before moving forward two more.



```ghost
    hoc22.clayGolemMoveForward(1)
    hoc22.waitForBlock()
    for (let index = 0; index < 2; index++) {    }
```
```template
    hoc22.clayGolemMoveForward(2) 
    hoc22.clayGolemMoveForward(2)    
```
```package
minecraft-hoc22=github:ReWrite-Media/hoc22-ts
```