### @flyoutOnly true
### @hideIteration true
### @explicitHints true


# Block Breaker

## Step 1
استخدم المؤشر لكسر البلوكات الموجودة أمام الباب للهروب.

الكود يحتوي على أخطاء، هل يمكنك إصلاحه؟ قم بتصحيح الكود عن طريق تشغيله لمعرفة كيف يعمل، ثم عدل عليه ليصبح الحل صحيحا.

#### ~ tutorialhint 
استخدم ``||hoc22.cursor move <direction>||`` مع ``||hoc22.break block||``  لتكسير عدد كاف من البلوكات. ليس من الضروري تكسير جميع البلوكات، يكفي أن تكسر الكمية التي تسمح لك بالوصول إلى الباب.



```ghost
    hoc22.cursorMoveOrientationOneUp(1)
    hoc22.cursorMoveOrientationOneDown(1)
    hoc22.cursorMoveOrientationOneLeft(1)
    hoc22.cursorMoveOrientationOneRight(1)
    hoc22.breakBlock()
    for (let index = 0; index < 2; index++) {    }
```
```template  
    hoc22.cursorMoveOrientationOneRight(1)   
    hoc22.cursorMoveOrientationOneRight(1)     
```
```package
minecraft-hoc22=github:ReWrite-Media/hoc22-ts
```