### @flyoutOnly true
### @hideIteration true
### @explicitHints true


# قوة الضوء

## الخطوة الأولى
استخدم المؤشر لتشغيل جميع الأضواء. بمجرد أن تضيء جميع الأضواء، سيفتح الباب.

الكود يحتوي على أخطاء، هل يمكنك إصلاحه؟ قم بتصحيح الكود عن طريق تشغيله لمعرفة كيف يعمل، ثم عدل عليه ليصبح الحل صحيحا.

#### ~ tutorialhint  
استخدم بلوك ``||hoc22.تحريك المؤشر (الاتجاه)||`` لتختر الضوء، ثم استخدم بلوك  ``||hoc22.تشغيل||`` لتشغيله. يمكن أن يسهل استخدام بلوك ``||التكرار||`` الكود بشكل كبير، لكنه ليس ضروريًا.


```ghost
    hoc22.cursorMoveOrientationOneUp(1)
    hoc22.cursorMoveOrientationOneDown(1)
    hoc22.cursorMoveOrientationOneLeft(1)
    hoc22.cursorMoveOrientationOneRight(1)
    hoc22.toggleLight()
    for (let index = 0; index < 2; index++) {    }
```
```template  
    hoc22.cursorMoveOrientationOneRight(2)   
    hoc22.toggleLight() 
    hoc22.cursorMoveOrientationOneRight(2)   
    hoc22.toggleLight()        
```
```package
hoc22-ts-ar=github:ReWrite-Media/hoc22-ts-ar
```