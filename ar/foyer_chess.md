### @flyoutOnly true
### @hideIteration true
### @explicitHints true


# Chess Pieces

## Step 1
لقد أطلقنا سراح الملكة والملك، لكن الباب لا يزال مغلقا. يبدو أن القطع موضوعة في أماكن غير صحيحة. حاول نقلها إلى المواقع الصحيحة، لكي تتمكن من الهروب من هذا المكان أخيرا!

الكود يحتوي على أخطاء، هل يمكنك إصلاحه؟ قم بتصحيح الكود عن طريق تشغيله لمعرفة كيف يعمل، ثم عدل عليه ليصبح الحل صحيحا.

#### ~ tutorialhint 
يمثل لوح الشطرنج شبكة من التواريخ. ابحث في الغرفة لتحديد التواريخ التي يجب أن يتواجد فيها الملك والملكة، ثم استخدم ``||hoc22.move king <direction>||`` و ``||hoc22.move queen <direction>||``  لتحريكهم إلى مواقعهم الصحيحة.

```ghost
    hoc22.kingMove(Custom.ArrowUpOrange, 1)
    hoc22.queenMove(Custom.ArrowUpOrange, 1)

```
```template
    hoc22.kingMove(Custom.ArrowUpOrange, 3)
    hoc22.kingMove(Custom.ArrowLeftBlue, 1)
    hoc22.queenMove(Custom.ArrowRightYellow, 2)
    hoc22.queenMove(Custom.ArrowUpOrange,1)          
```

```package
minecraft-hoc22=github:ReWrite-Media/hoc22-ts
```