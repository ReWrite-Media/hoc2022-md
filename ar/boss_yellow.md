### @flyoutOnly true
### @hideIteration true
### @explicitHints true


# Pull the Lever

## Step 1
There's the lever! Move the Agent to the lever and then pull it down!

The included example code is broken, can you fix it? Debug the code by running it to see what it does and then edit it to the correct solution.

#### ~ tutorialhint 
Use the ``||hoc22.agent move||`` block to position the Agent in front of the lever, and then use ``||hoc22.pull lever down||`` to activate it!

```ghost
    hoc22.agentMove(SixDirection.Up, 2)
    hoc22.pullLeverDownLime()
```
```template
    hoc22.agentMove(SixDirection.Forward, 2)
```

```package
minecraft-hoc22=github:ReWrite-Media/hoc22-ts
```