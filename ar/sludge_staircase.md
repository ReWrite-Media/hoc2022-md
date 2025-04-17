### @flyoutOnly true
### @hideIteration true
### @explicitHints true


# السُلم

## الخطوة الأولى
استخدم المؤشر  لبناء درج للوصول إلى الطابق العلوي!

الكود يحتوي على أخطاء، هل يمكنك إصلاحه؟ قم بتصحيح الكود عن طريق تشغيله لمعرفة كيف يعمل، ثم عدل عليه ليصبح الحل صحيحا.

#### ~ tutorialhint 
``||hoc22.تحريك المؤشر (الاتجاه)||`` وبلوك ``||hoc22.وضع كتلة||`` لإنشاء درج يمكنك كلاعب التسلق عليه، تأكد من بناء على الأقل بلوك واحد في كل مرة، مما يتيح لك القفز فوقه. حاول تعديل الكود الحالي بدلاً من البدء من الصفر.


```ghost
    hoc22.cursorMoveOrientationOneUp(1)
    hoc22.cursorMoveOrientationOneDown(1)
    hoc22.cursorMoveOrientationOneLeft(1)
    hoc22.cursorMoveOrientationOneRight(1)
    hoc22.placeBlock()
    for (let index = 0; index < 2; index++) {}
```
```template
    hoc22.placeBlock()
    hoc22.cursorMoveOrientationOneRight(2)   
    hoc22.placeBlock() 
```
```package
minecraft-hoc22-ts-ar=github:ReWrite-Media/hoc22-ts-ar
```