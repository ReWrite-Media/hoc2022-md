### @flyoutOnly true
### @hideIteration true
### @explicitHints true


# Pipes

## Step 1
You'll need to add a specific amount of blocks to each of the hoppers. Maybe there is something in the room that can tell you how many?

The included example code is broken, can you fix it? Debug the code by running it to see what it does and then edit it to the correct solution.

#### ~ tutorialhint 
Count how many blocks are on the landing behind the puzzle. Use the ``||hoc.drop <number> <color>||`` block to add that many blocks to the hoppers.



```ghost
    hoc22.summonColoredBlockMagenta(1)
    hoc22.summonColoredBlockLightBlue(1)
    hoc22.summonColoredBlockYellow(1)
    hoc22.summonColoredBlockLime(1)
```
```template
    hoc22.summonColoredBlockYellow(1)
    hoc22.summonColoredBlockYellow(1)
    hoc22.summonColoredBlockYellow(1)
    hoc22.summonColoredBlockLightBlue(1) 
    hoc22.summonColoredBlockMagenta(1)
      
```
```package
minecraft-hoc22=github:ReWrite-Media/hoc22-ts
```