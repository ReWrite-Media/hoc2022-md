### @flyoutOnly true
### @hideIteration true
### @explicitHints true


# Wrong Reflection

## Step 1
القرع الموجود فوق المدفأة، في المرآة يبدو مختلفا قليلا عن القرع الموجود في هذه الغرفة. حاول جعلها تتطابق.

الكود يحتوي على أخطاء، هل يمكنك إصلاحه؟ قم بتصحيح الكود عن طريق تشغيله لمعرفة كيف يعمل، ثم عدل عليه ليصبح الحل صحيحا.

#### ~ tutorialhint  
قم بتحريك المؤشر فوق المدفأة باستخدام  ``||hoc22.cursor move <direction>||`` لتحدد الموقع، ثم استخدم ``||hoc22.place pumpkin||`` لوضع القرع في ذلك الموقع

```ghost
    hoc22.cursorMoveOrientationOneUp(1)
    hoc22.cursorMoveOrientationOneDown(1)
    hoc22.cursorMoveOrientationOneLeft(1)
    hoc22.cursorMoveOrientationOneRight(1)
    hoc22.placePumpkin()
    for (let index = 0; index < 2; index++) {}

```
```template
    hoc22.cursorMoveOrientationOneLeft(1)
    hoc22.placePumpkin()
    hoc22.cursorMoveOrientationOneLeft(1)
    hoc22.placePumpkin()
    hoc22.cursorMoveOrientationOneLeft(1)
    hoc22.placePumpkin()
    hoc22.cursorMoveOrientationOneLeft(1)
```

```package
minecraft-hoc22=github:ReWrite-Media/hoc22-ts
```