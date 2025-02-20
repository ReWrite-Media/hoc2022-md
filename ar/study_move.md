### @flyoutOnly true
### @hideIteration true
### @explicitHints true


# Agent Move

## Step 1
Move the clay ball to the Gold block. Interact with the lightbulb if you need help. Try running the default code to see what happens. Then, make any changes you need to solve the puzzle. This is called debugging.

The included example code is broken, can you fix it? Debug the code by running it to see what it does and then edit it to the correct solution.

#### ~ tutorialhint  
Use ``||hoc22.clay ball move <direction> by <number>||`` to move the clay ball onto the Gold block. Adjust the direction variable and how many blocks down it moves in order to reach the Gold block.

```ghost
    hoc22.clayBallMove(FourDirectionUpDown.Up, 5)
```
```template
    hoc22.clayBallMove(FourDirectionUpDown.Up, 3)
    hoc22.clayBallMove(FourDirectionUpDown.Left, 2)
    hoc22.clayBallMove(FourDirectionUpDown.Down 3)
```

```package
minecraft-hoc22=github:ReWrite-Media/hoc22-ts
```