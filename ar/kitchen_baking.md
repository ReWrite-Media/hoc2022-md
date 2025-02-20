### @flyoutOnly true
### @hideIteration true
### @explicitHints true


# Bake Bread

## Step 1
The Zombie Chef needs help making bread. Use the code blocks to create a recipe the Zombie Chef can follow.

The included example code is broken, can you fix it? Debug the code by running it to see what it does and then edit it to the correct solution.

#### ~ tutorialhint 
Think about the order of operations it takes to make bread. You'd first ``||hoc22.harvest wheat||``, but then what? There are exactly four steps.

```ghost
    hoc22.bakingBreadWheat()
    hoc22.bakingBreadGrain()
    hoc22.bakingBreadDough()
    hoc22.bakingBreadBread()
```
```template
    hoc22.bakingBreadWheat()
    hoc22.bakingBreadDough()
    hoc22.bakingBreadBread()
    hoc22.bakingBreadGrain()
```

```package
minecraft-hoc22=github:ReWrite-Media/hoc22-ts
```