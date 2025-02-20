### @flyoutOnly true
### @hideIteration true
### @explicitHints true


# Unlock the Trap

## Step 1
Now we have the chance to capture the Time Agents! We need to align all 3 colored discs to trap the Time Agents.

The included example code is broken, can you fix it? Debug the code by running it to see what it does and then edit it to the correct solution.

#### ~ tutorialhint 
Rotate each section using the ``||hoc22.rotate <section> <direction> by <number>||`` blocks. Line up the colored paths between both sections. Once that's done, we should be able to finally put a stop to those Time Agents!

```ghost
    hoc22.outerRingClockwise(1)
    hoc22.outerRingCounterclockwise(1)
    hoc22.middleRingClockwise(1)
    hoc22.middleRingCounterclockwise(1)
    hoc22.innerRingCounterclockwise(1)
    hoc22.innerRingClockwise(1)
```
```template       
    hoc22.outerRingClockwise(1)
    hoc22.middleRingCounterclockwise(3)

```

```package
minecraft-hoc22=github:ReWrite-Media/hoc22-ts
```