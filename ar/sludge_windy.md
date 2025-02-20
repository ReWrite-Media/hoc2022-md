### @flyoutOnly true
### @hideIteration true
### @explicitHints true


# Windy Bridge

## Step 1
استخدم المؤشر الخاص بك لحجب الرياح، حتى تتمكن من عبور الجسر.

الكود يحتوي على أخطاء، هل يمكنك إصلاحه؟ قم بتصحيح الكود عن طريق تشغيله لمعرفة كيف يعمل، ثم عدل عليه ليصبح الحل صحيحا.

#### ~ tutorialhint 
استخدم ``||hoc22.cursor move||`` لوضع المؤشر أمام الثقوب، ثم استخدم ``||hoc22.place block||`` لملء الثقوب وحجب الرياح.



```ghost
    hoc22.cursorMoveOrientationOneUp(1)
    hoc22.cursorMoveOrientationOneDown(1)
    hoc22.cursorMoveOrientationOneLeft(1)
    hoc22.cursorMoveOrientationOneRight(1)
    hoc22.placeBlock()
```
```template
    hoc22.cursorMoveOrientationOneRight(1)   
    hoc22.placeBlock()
```
```package
minecraft-hoc22=github:ReWrite-Media/hoc22-ts
```