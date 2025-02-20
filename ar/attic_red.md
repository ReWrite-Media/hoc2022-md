### @flyoutOnly true
### @hideIteration true
### @explicitHints true


# Attic Tutorial

## Step 1
To open the Red door, both you and the Agent will have to work together. Flip the lever to bring up the iron wall, then move the Agent so it is above the Gold blocks in front of the Red door.

The included example code is broken, can you fix it? Debug the code by running it to see what it does and then edit it to the correct solution.

#### ~ tutorialhint 
Flip the lever down to bring up the iron wall, then move the Agent 14 blocks forward using ``||hoc22.agent move <direction> by <number>||``



```ghost
    hoc22.agentMove(SixDirection.Up, 1)
```
```template
    hoc22.agentMove(SixDirection.Forward, 10)     
```
```package
minecraft-hoc22=github:ReWrite-Media/hoc22-ts
```