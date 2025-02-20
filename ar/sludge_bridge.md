### @flyoutOnly true
### @hideIteration true
### @explicitHints true


# Bridge Builder

## Step 1
استخدم المؤشر الخاص بك لبناء جسر يساعد حامل الصندوق في الوصول إلى الزر! سيظهر درج للصعود بمجرد أن يقوم حامل الصندوق بالضغط على الزر.

الكود يحتوي على أخطاء، هل يمكنك إصلاحه؟ قم بتصحيح الكود عن طريق تشغيله لمعرفة كيف يعمل، ثم عدل عليه ليصبح الحل صحيحا.

#### ~ tutorialhint  
استخدم ``||hoc22.cursor move <direction>||`` مع ``||hoc22.place block||`` لإنشاء جسر يصل إلى الزر. سيقوم مونين بالسير نحو الزر والضغط عليه بمجرد بناء الجسر له.



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
minecraft-hoc22=github:ReWrite-Media/hoc22-ts
```