### @flyoutOnly true
### @hideIteration true
### @explicitHints true


# Minecart Redirection

## Step 1
Deliver each mob to their correct place. Look at the mobs lined up and change the code to make sure they arrive in the order they are waiting.

The included example code is broken, can you fix it? Debug the code by running it to see what it does and then edit it to the correct solution.

#### ~ tutorialhint 
Use the ``||hoc22.sort||`` blocks to send the mobs to the correct passageways. They will be released from right to left, so make sure you order them correctly in your code.



```ghost
    hoc22.minecraftSortingZombie(1)
    hoc22.minecraftSortingSkeleton(1)
    hoc22.minecraftSortingCreeper(1)
```
```template
    hoc22.minecraftSortingZombie(1)
    hoc22.minecraftSortingSkeleton(1)
    hoc22.minecraftSortingCreeper(1)
    hoc22.minecraftSortingZombie(1)
    hoc22.minecraftSortingSkeleton(1)
```
```package
minecraft-hoc22=github:ReWrite-Media/hoc22-ts
```