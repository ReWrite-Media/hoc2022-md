### @flyoutOnly true
### @hideIteration true
### @explicitHints true


# الكشف عن الليزر

## الخطوة الأولى
املأ جميع الثقوب في الأرضية باستخدام المؤشر لفتح الستارة الحمراء.

الكود يحتوي على أخطاء، هل يمكنك إصلاحه؟ قم بتصحيح الكود عن طريق تشغيله لمعرفة كيف يعمل، ثم عدل عليه ليصبح الحل صحيحا.

#### ~ tutorialhint  
قم بملء جميع الثقوب في الأرضية باستخدام بلوك ``||hoc22.تحريك المؤشر||`` لتحديد موضع المؤشر وثم استخدم بلوك ``||hoc22.وضع كتلة||`` لملء الثقوب



```ghost
    hoc22.cursorMoveOrientationOneUp(1)
    hoc22.cursorMoveOrientationOneDown(1)
    hoc22.cursorMoveOrientationOneLeft(1)
    hoc22.cursorMoveOrientationOneRight(1)
    hoc22.placeBlock()
```
```template  
    hoc22.placeBlock()
    hoc22.cursorMoveOrientationOneUp(3)       
    hoc22.placeBlock() 
    hoc22.cursorMoveOrientationOneRight(5)
```
```package
minecraft-hoc22=github:ReWrite-Media/hoc22-ts
```