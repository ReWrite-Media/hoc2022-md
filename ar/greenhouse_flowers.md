### @flyoutOnly true
### @hideIteration true
### @explicitHints true


# زراعة الأزهار

## الخطوة الأولى
يبدو أن هناك نمطا معينا يجب اتباعه في هذه الحديقة. ربما تكون الأحواض الموجودة على اليسار واليمين هي الأدلة؟

الكود يحتوي على أخطاء، هل يمكنك إصلاحه؟ قم بتصحيح الكود عن طريق تشغيله لمعرفة كيف يعمل، ثم عدل عليه ليصبح الحل صحيحا.

#### ~ tutorialhint 
قم بتحريك المؤشر باستخدام كتلة ``||hoc22.تحريك المؤشر (الاتجاه)||`` ، ثم استخدم كتلة ``||hoc22.وضع (زهرة)||`` لتنسيق زهرة بشكل صحيح. بعد ذلك، قم بملء حوض الأزهار بالكامل من خلال مطابقة النمط الموجود على اليسار مع النمط على اليمين لإكمال اللغز.


```ghost
    hoc22.cursorMoveOrientationOneUp(1)
    hoc22.cursorMoveOrientationOneDown(1)
    hoc22.cursorMoveOrientationOneLeft(1)
    hoc22.cursorMoveOrientationOneRight(1)
    hoc22.flowerPlantingRedFlower()
    hoc22.flowerPlantingYellowFlower()
    hoc22.flowerPlantingBlueFlower()
    for (let index = 0; index < 2; index++) {}
```
```template
    hoc22.flowerPlantingBlueFlower() 
    hoc22.cursorMoveOrientationOneRight(3)    
    hoc22.cursorMoveOrientationOneDown(1) 
    hoc22.flowerPlantingYellowFlower()  
    hoc22.cursorMoveOrientationOneLeft(1)   
    hoc22.cursorMoveOrientationOneDown(1) 
    hoc22.flowerPlantingRedFlower()    
```
```package
minecraft-hoc22=github:ReWrite-Media/hoc22-ts
```