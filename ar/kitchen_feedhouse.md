### @flyoutOnly true
### @hideIteration true
### @explicitHints true


# إطعام المنزل

## الخطوة الأولى
المنزل جائع! وما أفضل من التفاح، والسلمون، ومرق الفطر لإطعامه! حاول أن تعرف الكمية التي يحتاجها المنزل من كل مكون.

الكود يحتوي على أخطاء، هل يمكنك إصلاحه؟ قم بتصحيح الكود عن طريق تشغيله لمعرفة كيف يعمل، ثم عدل عليه ليصبح الحل صحيحا.

#### ~ tutorialhint  
انتبه لعدد الطهاة الزومبي الذين يمرون مع كل مكون. استخدم بلوك ``||hoc22.feed house <ingredient>||`` لتزويد المنزل بالكمية المطلوبة.

```ghost
    hoc22.feedHouseApple(1)
    hoc22.feedHouseSalmon(1)
    hoc22.feedHouseMushroomStew(1)

```
```template
    hoc22.feedHouseApple(2)
    hoc22.feedHouseSalmon(1)
```

```package
minecraft-hoc22=github:ReWrite-Media/hoc22-ts
```