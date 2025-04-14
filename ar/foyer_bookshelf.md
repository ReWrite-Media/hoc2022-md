### @flyoutOnly true
### @hideIteration true
### @explicitHints true


# درج المكتبة

## الخطوة الأولى
يبدو أن هناك شيئا في أعلى خزانة الكتب. حاول أن تجد وسيلة للوصول إلى هناك.

الكود يحتوي على أخطاء، هل يمكنك إصلاحه؟ قم بتصحيح الكود عن طريق تشغيله لمعرفة كيف يعمل، ثم عدل عليه ليصبح الحل صحيحا.

#### ~ tutorialhint 
قم بتحريك المؤشر عبر المكتبة لاختيار موقع باستخدام بلوك ``||hoc22.تحريك المؤشر (الاتجاه)||`` ، ثم استخدم بلوك ``||hoc22.وضع كتلة||`` لوضع البلوك في الموقع المحدد، ثم اصنع درجا للوصول إلى القمة.

```ghost
    hoc22.cursorMoveOrientationOneUp(1)
    hoc22.cursorMoveOrientationOneDown(1)
    hoc22.cursorMoveOrientationOneLeft(1)
    hoc22.cursorMoveOrientationOneRight(1)
    hoc22.placeBlock()
    for (let index = 0; index < 4; index++) {    }

```
```template
    hoc22.placeBlock()        
    hoc22.cursorMoveOrientationOneRight(3)
    hoc22.placeBlock()
    hoc22.cursorMoveOrientationOneRight(3)
    hoc22.placeBlock()
```

```package
minecraft-hoc22=github:ReWrite-Media/hoc22-ts
```