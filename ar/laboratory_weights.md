### @flyoutOnly true
### @hideIteration true
### @explicitHints true


# Weights

## Step 1
تحتاج إلى استخدام الميزان للحصول على الوزن الإجمالي وهو 23 بدقة. هل من الممكن أن تكون هناك لافتة قريبة تحتوي على أوزان ؟

الكود يحتوي على أخطاء، هل يمكنك إصلاحه؟ قم بتصحيح الكود عن طريق تشغيله لمعرفة كيف يعمل، ثم عدل عليه ليصبح الحل صحيحا.

#### ~ tutorialhint  
استخدم `||hoc22.summon <mob>||`  لاستدعاء الكائنات للوصول إلى الوزن الإجمالي قدره 23. وزن الدجاجة هو 1، ووزن الخروف هو 3، ووزن البقرة هو 5.



```ghost
    hoc22.summonWeightChicken(1)
    hoc22.summonWeightCow(1)
    hoc22.summonWeightSheep(1)
```
```template
    hoc22.summonWeightSheep(1)
    hoc22.summonWeightCow(1)
    hoc22.summonWeightChicken(1)
      
```
```package
minecraft-hoc22=github:ReWrite-Media/hoc22-ts
```