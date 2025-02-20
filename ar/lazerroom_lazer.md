### @flyoutOnly true
### @hideIteration true
### @explicitHints true


# Laser Puzzle

## Step 1
تعيق البلوكات الصلبة أشعة الليزر! قم بتحريك الصفوف الخضراء والصفراء على الأرض لتمر أشعة الليزر عبر البلوكات الزجاجية وتشغل الضوء في الجهة الأخرى.

الكود يحتوي على أخطاء، هل يمكنك إصلاحه؟ قم بتصحيح الكود عن طريق تشغيله لمعرفة كيف يعمل، ثم عدل عليه ليصبح الحل صحيحا.

#### ~ tutorialhint  
استخدم ``||hoc22.shift||`` لتختر الصف الذي ترغب في نقله والاتجاه الذي يجب أن يتحرك فيه باستخدام البلوكات. سيتم دفع البلوك الموجود في نهاية الصف الذي تقوم بتحريكه إلى الجهة الأخرى.



```ghost
    hoc22.GreenLeftLaser(1)
    hoc22.GreenRightLaser(1)

```
```template
    hoc22.GreenLeftLaser(1)
      
```
```package
minecraft-hoc22=github:ReWrite-Media/hoc22-ts
```