### @flyoutOnly true
### @hideIteration true
### @explicitHints true


# Cannons

## Step 1
كل مدفع يتميز بلونه الفريد من الأشعة. يجب عليك تفعيل المدافع بالترتيب الذي تظهر به الحلقات الملونة حول كرة الزمن.

الكود يحتوي على أخطاء، هل يمكنك إصلاحه؟ قم بتصحيح الكود عن طريق تشغيله لمعرفة كيف يعمل، ثم عدل عليه ليصبح الحل صحيحا.

#### ~ tutorialhint 
انتبه جيدا إلى الحلقات الملونة المحيطة بكرة الزمن. استخدم  ``||hoc22.activate <color> cannon||`` لمطابقة ترتيب الحلقات حول كرة الزمن. ابدأ من الحلقة الخارجية وانتقل نحو الداخل.

```ghost
    hoc22.magentaCannon()
    hoc22.lightBlueCannon()
    hoc22.limeCannon()
    hoc22.yellowCannon()
```
```template       
    hoc22.yellowCannon()
    hoc22.lightBlueCannon()
    hoc22.magentaCannon()
    hoc22.limeCannon()
    
```

```package
minecraft-hoc22=github:ReWrite-Media/hoc22-ts
```