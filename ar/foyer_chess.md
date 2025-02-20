### @flyoutOnly true
### @hideIteration true
### @explicitHints true


# Chess Pieces

## Step 1
We've freed the King and Queen, but the door still isn't opening. The pieces must be in the wrong places. Move them into the correct places, so you can finally escape this place!

The included example code is broken, can you fix it? Debug the code by running it to see what it does and then edit it to the correct solution.

#### ~ tutorialhint 
The chessboard represents a grid of dates. Search the room to figure out what dates the king and queen should be on and then use the ``||hoc22.move king <direction>||`` and ``||hoc22.move queen <direction>||`` blocks to move them into their correct positions.

```ghost
    hoc22.kingMove(Custom.ArrowUpOrange, 1)
    hoc22.queenMove(Custom.ArrowUpOrange, 1)

```
```template
    hoc22.kingMove(Custom.ArrowUpOrange, 3)
    hoc22.kingMove(Custom.ArrowLeftBlue, 1)
    hoc22.queenMove(Custom.ArrowRightYellow, 2)
    hoc22.queenMove(Custom.ArrowUpOrange,1)          
```

```package
minecraft-hoc22=github:ReWrite-Media/hoc22-ts
```