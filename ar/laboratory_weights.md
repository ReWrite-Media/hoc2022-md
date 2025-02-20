### @flyoutOnly true
### @hideIteration true
### @explicitHints true


# Weights

## Step 1
You need the scale to reach the total weight of exactly 23. Maybe there is a sign around with mob weights?

The included example code is broken, can you fix it? Debug the code by running it to see what it does and then edit it to the correct solution.

#### ~ tutorialhint 
Use the `||hoc22.summon <mob>||` blocks to spawn in mobs to get a total weight of 23. A chicken is 1, a sheep is 3, and a cow is 5.



```ghost
    hoc22.summonWeightChicken(1)
    hoc22.summonWeightCow(1)
    hoc22.summonWeightSheep(1)
```
```template
    hoc22.summonWeightSheep(1)
    hoc22.summonWeightCow(1)
    hoc22.summonWeightChicken(1)
      
```
```package
minecraft-hoc22=github:ReWrite-Media/hoc22-ts
```