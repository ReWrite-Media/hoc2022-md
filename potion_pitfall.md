### @flyoutOnly true
### @hideIteration true
### @explicitHints true


# Potion Room - Pitfall

## Step 1
Move the zombie forward 6 blocks. When the zombie steps on a pressure place it will open a pit for 1 second, so make it wait for the block to come back before moving forward. 

#### ~ tutorialhint 
Move the zombie forward by using the ``||hoc22.move zombie forward by <number>||`` block. Move the zombie forward 2 blocks and then use ``||hoc22.wait for block||`` to have the zombie wait 1 second before moving forwad two more.



```ghost
    hoc22.zombieMoveForward(1)
    hoc22.waitForBlock()
    for (let index = 0; index < 2; index++) {    }
```
```template
    hoc22.zombieMoveForward(2) 
    hoc22.zombieMoveForward(2)    
```
```package
minecraft-hoc22=github:ReWrite-Media/hoc22-ts#v0.2.77
```
