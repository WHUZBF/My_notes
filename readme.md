# 这是我自学格里菲斯量子力学的LaTex笔记

## 简介
本人是武汉大学物理学院21级本科生，这份笔记主要是大一下空闲时间为了练习LaTex基本语法和巩固所学量子力学知识敲成的，并不是课本的总结，而是自己的推导加上个人的理解以及其它课本的思想内容的结晶。笔记主要用于自查，不保证正确性(~~不过还是查找很多资料了的~~)。课内的学习也比较繁忙，而且我学习量子力学的话最多每天学一节，再加上有时候排版也会出些问题，所以更新和学习频率都比较慢，不过我自认为还是慢点学，学懂为主，不求快(**话说前三个月我才看了三章**)。

## 源代码简介
这学期是我第一次用Latex排版这么大的篇幅，我没想到要整理的笔记篇幅已经远远超出我的预期，然而我一直使用的是report，避免不必要的麻烦，所以我索性不更改排版类型。而且排版技术也在进步，所以可以看到我的笔记越到后面排版的越好(~~大概~~)。前面的排版要修正比较麻烦，索性就不改了。而且我排版一直没有分章节排版，源代码里就一个源文件，之后的排版还是用report为主(✔，我要不断完善屎山代码)，不过我会每个章节排版完成后更新一个book，当然，这部分就是粗校了，大致看看有没有意想不到的错误。

不是太会用git，所以分支管理这些的很糟糕。。。。目前就会push和pull。。。(~~但也懒得学~~)

sourcecode开头的是源码，也是文章主题，appendix开头的是文章附录，fig文件夹里面放的是note里面的图片，MMASouceCode文件夹里面放的是与note有关的一些mathematica源码(版本12.0)，videos文件夹里面放的是note里面的动画GIF(我也没想到原来可以通过Latex在pdf里面插入动画。。。。)

这个很帅的封面不是我自己用tikz写的，咱也没那能力，来源于：[封面 - LaTeX 工作室 (latexstudio.net)](https://www.latexstudio.net/index/details/index/mid/3121.html)

这个很牛逼的封底也不是我自己写的，自己做了点改动，来源于[GTM封底 - LaTeX 工作室 (latexstudio.net)](https://www.latexstudio.net/index/details/index/mid/2719.html)

## 参考书籍

主要参考的就是*Griffiths*的量子力学英文版和*Cohen*的大部头，比如第三章的形式理论讲述的方式和*Griffiths*的就有很大的不同，直接引入Dirac符号，正是*Cohen*书中第二章的内容。向量分析附录主要参考的是*Mathews*的*Vector Calculus*，内容基础但是讲的非常细致(~~非常适合我这种渣渣~~)。

附录的群论部分有限群参考李新征老师讲义，置换群和SO(3)部分主要参考*Wu-Ki Tung*群论书籍以及群论上课时的笔记。

路径积分部分费曼自己有过一本比较好的书，这个内容还是在量子场论中学习比较好，我这里主要是参考的曾谨言的书。

另外还看了下[斯坦福教授莱昂纳德的理论物理量子力学讲座](https://www.bilibili.com/video/BV1Wa411Y7gC?spm_id_from=333.337.search-card.all.click)。也参考了*David Tong*[量子力学部分的讲义](http://www.damtp.cam.ac.uk/user/tong/quantum.html)。国内的中文书也经常查，可以补充一些遗漏的地方。这部分中文书主要看的就是顾樵的两卷，中规中矩，讲的也很细致。

当然我读的是英文版，要用英文入门一个全新的领域还是很困难的，不过先读一个星期习惯作者的语言风格了就好。目前这本书英文版是第三版，国内有第二版的翻译版。不过翻译的是**真的烂**，不过有时候我也对照着看看，相当于凑合着看本书第二版，有的地方我感觉第二版讲的比第三版好。当然格里菲斯这本书越学越觉得读完了只能大概知道怎么解薛定谔方程，知道一些量子力学里面非常初步的概念。而且第三版还增厚了许多。所以看完前半部分理论部分我可能就打算读点高级的书(~~当然继续啃完这本书也不是不可以~~)。

最后就是习题

**学物理不做习题，就像和女友通过书信生出孩子——费曼**

这部分推荐的就是格里菲斯的习题全部，习题都非常有启发意义，而且网上也有*Griffiths*自己写的答案。再就是一本比较老的习题集*Selected Problems in quantum mechanics* 作者是*D.ter Haar*。我目前只做了第一章，很多题型都覆盖到了。

# 附录说明

这本笔记的附录是个大杂烩

首先是附录A，大一上的时候在图书馆闲逛看见了Mathews的*Vector Calculus*，学完之后觉得爱因斯坦求和和张量真是奇妙，所以写了这个note，当然是比较浅显的矢量微积分，现在我早忘了拉梅系数了，都是直接用度规张量。

然后是附录B，这是在后面学量子力学的时候发现线性代数甚是重要加上自己在大一寒假看过*Linear Algebra Done Right*，所以结合Cohen的书第二章写了个物理版本的线性代数入门。

附录C是因为计算题经常出现各种高斯积分，每次都去网上查或者自己手撕有点难搞，刚好在知乎上看见了一篇文章（那天找到链接了再补），然后就顺势抄下来了作为一个积分表附录。

附录D是因为群论和量子力学那简直关系密切，初量自然用不上，不过马上要学高量，而且也不想新开个笔记专门写群论，所以就作为附录了，只打算写有限群，参考的是李新征老师讲义的第一二章和最后一章，置换群那里看了点马中骥先生的书。

#  一些计划 

- [ ] 最后附录补一下有限差分法(FDM)的相关内容
- [ ] 相对论量子力学部分附录补一下
- [x] 群论附录

# 后记

格里菲斯这本书读完前半部分理论部分后我打算先暂停笔记的更新，定态微扰那些计算理论暂时先不看，继续去看Sakurai的摩登量子力学，把基础概念再强化一下，而且还有很厚的Goldstein需要研读，所以可能也没有时间再认真写笔记了。等有时间了一定会继续读完格里菲斯补完笔记，我估计格里菲斯看完，Sakura看一看，有时间再研读下Cohen的书，量子力学应该就差不多了，不过我应该会多读几遍量子力学圣经——Dirac的著作。对量子力学理解的越深，我应该就会回来不断完善这个笔记，最终就不限于格里菲斯的书了。（~~woc，我画了好大一个饼，这些认真看完我估计我都大学快毕业了~~）

22.11.2 update 额😓大二上学期的模电和其它各种事导致Griffith可能要看整整一年了🤣。不知道Sakurai和QFT啥时候可以开始。

23.1.17 update 不知为啥这几天vscode的tex插件好像都很慢，很难加载成功，所以换为TexStudio进行开发。

23.6.24 update 这个readme很久没有更新了，现在第二遍量子力学已经大致上学完一遍了，用的时喀兴林的高等量子力学，下学期估计还会用Sakurai的书再学一遍，喀兴林老师的书比较难读，但是逻辑十分严谨，我读的时候是反反复复品味，书都快翻烂，现在打算回过头来重新整理笔记。这篇笔记很不成熟，很多地方都是抄*Griffiths*书，现在对量子力学理解得更深，特别是群论部分的理解，所以现在慢慢的在改正笔记中讲的不好的地方甚至是错误的地方。特别是会花上比较多的时间把量子力学对称性部分按照喀兴林先生的讲法好好重新写一遍，这大致就是我暑期要干的事情，若是时间够了也会把二次量子化内容补一下。含时微扰论只能等下学期了，另外量子信息和量子计算我想找找**高能方面相关**的书籍看了之后再回来补。

24.2.9 update 现在处于半弃坑状态，毕竟要写的东西太多，目前已经过了学量子力学打基础的阶段，可能不会再更新了，或许会抽某天（可能N年之后）补完含时微扰论之后完结撒花。后面更新主要就是针对个人对QM新的理解进行，一点点打补丁，就比如最近看书就对AB效应有了新的理解。

# 联系方式

如果发现笔记中存在问题，欢迎讨论！！！

qqEmail：1271570053@qq.com

学校邮箱：2021302022016@whu.edu.cn(~~话说当时为什么不设计一个好点的别名。。。~~)