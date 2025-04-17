### @flyoutOnly true
### @hideIteration true
### @explicitHints true


# بناء الجسور

## الخطوة الأولى
استخدم المؤشر الخاص بك لبناء جسر يساعد حامل الصندوق في الوصول إلى الزر! سيظهر درج للصعود بمجرد أن يقوم حامل الصندوق بالضغط على الزر.

الكود يحتوي على أخطاء، هل يمكنك إصلاحه؟ قم بتصحيح الكود عن طريق تشغيله لمعرفة كيف يعمل، ثم عدل عليه ليصبح الحل صحيحا.

#### ~ tutorialhint  
استخدم بلوك ``||hoc22.تحريك المؤشر (الاتجاه)||`` مع بلوك ``||hoc22.وضع كتلة||`` لإنشاء جسر يصل إلى الزر. سيقوم كائن المونين بالسير نحو الزر والضغط عليه بمجرد بناء الجسر له.


```ghost
    hoc22.cursorMoveOrientationOneUp(1)
    hoc22.cursorMoveOrientationOneDown(1)
    hoc22.cursorMoveOrientationOneLeft(1)
    hoc22.cursorMoveOrientationOneRight(1)
    hoc22.placeBlock()
    for (let index = 0; index < 2; index++) {    }
```
```template
    hoc22.placeBlock()
    hoc22.cursorMoveOrientationOneRight(2)  
    hoc22.placeBlock() 
```
```package
minecraft-hoc22-ts-ar=github:ReWrite-Media/hoc22-ts-ar
```