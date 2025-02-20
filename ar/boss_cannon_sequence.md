### @flyoutOnly true
### @hideIteration true
### @explicitHints true


# Cannons

## Step 1
Each cannon has its own beam color. Activate the cannons in the same order as the colored rings surrounding the Time Orb.

The included example code is broken, can you fix it? Debug the code by running it to see what it does and then edit it to the correct solution.

#### ~ tutorialhint 
Pay close attention to the colored rings around the Time Orb. Use the ``||hoc22.activate <color> cannon||`` blocks to match the order of rings around the Time Orb. Start from the outer most ring and work your way in.

```ghost
    hoc22.magentaCannon()
    hoc22.lightBlueCannon()
    hoc22.limeCannon()
    hoc22.yellowCannon()
```
```template       
    hoc22.yellowCannon()
    hoc22.lightBlueCannon()
    hoc22.magentaCannon()
    hoc22.limeCannon()
    
```

```package
minecraft-hoc22=github:ReWrite-Media/hoc22-ts
```