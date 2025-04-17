### @flyoutOnly true
### @hideIteration true
### @explicitHints true


# تحريك الروبوت

## الخطوة الأولى
قم بتحريك كرة الطين نحو البلوك الذهبي. تفاعل مع المصباح إذا كنت بحاجة إلى مساعدة. جرب تشغيل الكود الحالي لترى ما يحدث. بعد ذلك، قم بإجراء أي تغييرات تحتاجها لحل اللغز. يطلق على ذلك اسم تصحيح الأخطاء.

الكود يحتوي على أخطاء، هل يمكنك إصلاحه؟ قم بتصحيح الكود عن طريق تشغيله لمعرفة كيف يعمل، ثم عدل عليه ليصبح الحل صحيحا.

#### ~ tutorialhint  
استخدم ``||hoc22.تحريك كرة الطين (الاتجاه) بمقدار (العدد)||`` لتحريك كرة الطين باتجاه البلوك الذهبي. قم بتعديل متغير الاتجاه وعدد البلوكات التي تتحرك بها حتى تصل إلى البلوك الذهبي.

```ghost
    hoc22.clayBallMove(FourDirectionUpDown.Up, 5)
```
```template
    hoc22.clayBallMove(FourDirectionUpDown.Up, 3)
    hoc22.clayBallMove(FourDirectionUpDown.Left, 2)
    hoc22.clayBallMove(FourDirectionUpDown.Down 3)
```

```package
minecraft-hoc22-ts-ar=github:ReWrite-Media/hoc22-ts-ar
```