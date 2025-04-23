### @flyoutOnly true
### @hideIteration true
### @explicitHints true


# تحطيم الكتل

## الخطوة الأولى
استخدم المؤشر لكسر البلوكات الموجودة أمام الباب للهروب.

الكود يحتوي على أخطاء، هل يمكنك إصلاحه؟ قم بتصحيح الكود عن طريق تشغيله لمعرفة كيف يعمل، ثم عدل عليه ليصبح الحل صحيحا.

#### ~ tutorialhint 
استخدم بلوك ``||hoc22.تحريك المؤشر (الاتجاه)||`` مع بلوك ``||hoc22.كسر كتلة||`` لتكسير عدد كافٍ من البلوكات. ليس من الضروري تكسير جميع البلوكات، بل يكفي تكسير الكمية التي تتيح لك الوصول إلى الباب.


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
hoc22-ts-ar=github:ReWrite-Media/hoc22-ts-ar
```