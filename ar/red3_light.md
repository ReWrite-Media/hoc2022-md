### @flyoutOnly true
### @hideIteration true
### @explicitHints true


# Light Power

## Step 1
استخدم المؤشر لتشغيل جميع الأضواء. بمجرد أن تضيء جميع الأضواء، سيفتح الباب.

الكود يحتوي على أخطاء، هل يمكنك إصلاحه؟ قم بتصحيح الكود عن طريق تشغيله لمعرفة كيف يعمل، ثم عدل عليه ليصبح الحل صحيحا.

#### ~ tutorialhint  
استخدم  ``||hoc22.cursor move <direction>||`` لتختر الضوء، ثم استخدم  ``||hoc22.turn on||`` لتشغيله. استخدام حلقة سيسهل الكود كثيرا، لكنه ليس ضروريا.



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
minecraft-hoc22=github:ReWrite-Media/hoc22-ts
```