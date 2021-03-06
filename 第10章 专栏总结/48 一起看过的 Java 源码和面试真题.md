## 不为了源码而读源码，只为了更好的实践

持续几个月，我们的专栏终于结束了，这篇总结篇，我们又想回到当初写这篇专栏的初心：我们不为读源码而读源码，只是为了更好的实践。

我刚工作的时候，就有一些大佬推荐我来阅读 Java 源码，那时候的我懵懵懂懂，只觉得大佬说的是对的，于是就去读，当时的目的很简单，主要是两个：一个是应付面试，一个是想让自己更强。

当时边工作边读源码，一开始真心是一点都看不懂，逻辑都看得很迷糊，更不用说去探究作者为什么这么写，用到哪些设计模式了，但也不知道为什么，还是咬牙把源码都读完了。

读完之后，还是比较骄傲的，虽然说读完之后，很多细节都不记得了，但不知道为啥，总是有股莫名的自信，原来自己已经是读过源码的人了，而且在平时的工作中，用到一些 API 时，脑海中突然就会蹦出一些火花来：比如说初始化 List、Map 时如何初始化其大小；比如说如何根据场景来设置线程池；比如说如何根据业务写出优雅的锁，这时候就会自我感觉代码写的好，其实我一直有个理念：只有紧密贴合业务，能帮助解决业务复杂度的代码才是好代码，读了第一遍 Java 源码之后，突然就有了这种感觉，对自己写的代码也越来越有自信了。

随着工作年龄的增加，又陆续读过几次 Java 源码，现在除了对自己写代码的自信，还多了一种帮助别人的自信，在同事遇到困难，或者 代码 review 时，一些漏洞，你很容易就看出来，不知不觉你就会成为团队中的技术专家。

所以我们才一直强调，我们读源码真心是为了更好的实践，这种好处当你认真读完源码之后，慢慢就会感受到了。



## 同学们的问题

在这几个月内，我收到很多问题，但比较频繁的是两类问题，第一类问题主要是说自己看不懂源码，问我怎么办？这个问题其实我也没有答案，Java 源码本身就很枯燥，它并不是电视剧，也不是小说，它是需要我们静下心来，一行一行琢磨思考的东西，同学们都很聪明，不是看不懂，只是不想静下心来罢了。当然当代码太复杂时，我们只看也是不行的，需要亲自动手 debug。

第二类问题主要是作者为什么这么写？这个问题其实也很难回答，但问这些问题的同学，我基本都一一作答了，在和这些同学交流的过程中，发现一小部分同学的确对源码很有研究，我也受益匪浅，但大部分同学其实并没有搞懂源码本身的逻辑，试想如果在没有搞懂源码本身的逻辑下，又如何去猜测并理解原作者用代码的本意呢？恐怕很难，所以还是建议大家先把源码本身逻辑弄懂后，再去推测本意和设计模型，不然这又会成为你阅读源码的阻碍（话虽然难听，但是真心的建议）。



## 感谢

这是我第一篇在慕课网的专栏，非常感谢慕课网的编辑和商务，给我了很多帮助。

当然最要感激的是各位同学，虽然我们一直内部强调，专栏不求快，只求质量和内容，但 Java 源码实在博大精深，由于我个人的理解问题和笔误，的确出现了一些理解不当的地方和笔误，在同学们的包容和指正下，我们也一起做了更正，所以非常感谢同学的包容和指正，真心的感谢大家的包容，谢谢。

最后留下我的个人微信（luanqiu0）吧，真心想交流后端技术和架构的可以加我，当然其它的我也不会了，再次谢谢各位同学一起走过我们的专栏，来过，看过，希望你能有所收获，谢谢。

[47 工作实战：Socket 结合线程池的使用 ](http://www.imooc.com/read/47/article/889)

精选留言 17

欢迎在这里发表留言，作者筛选后可公开显示 

- [super_小小胡](http://www.imooc.com/u/8200009/articles)

  老师，请问下这个专栏有没有长期维护的，以后还有没有更新或者修改的呀 

   0

  回复

  1天前

- [没事看看书](http://www.imooc.com/u/7972128/articles)

  发现专栏里都是宝藏啊，感谢老师了 

   0

  回复

  2020-02-12

- [Starry_ZB](http://www.imooc.com/u/2832589/articles)

  谢谢老师，过了一遍感觉还没懂透，还要反复再读几次。 

   0

  回复

  2020-02-09

- [achilleskwok](http://www.imooc.com/u/2281301/articles)

  感谢，看了前几课，就来感谢作者，写的很好很深刻，一直想找专门分析JDK源码的书或者文章，一直找不到很适合的，在这里谢谢作者，希望能有更优秀的作品诞生，方便大家的学习。 

   0

  回复

  2020-02-05

- [taian_work](http://www.imooc.com/u/2704775/articles)

  新年快乐老师~~~~~~~ 

   1

  回复

  2020-02-02

- [weixin_慕UI1009709](http://www.imooc.com/u/8291152/articles)

  老师 读完了您的专栏，顺便也把一些看不懂的代码和jdk本地源码对比或者调试了，才有了一点感觉，谢谢您的专栏，帮我完成了 第一遍对源码的阅读。虽然我理解的很粗浅，但是对于java jdk api 本身确实有了 一点感觉，再遇见问题的时候首先去看的是源码，而不是网上搜索答案，谢谢。 

   0

  回复

  2020-01-13

- [南城阿宇](http://www.imooc.com/u/8195907/articles)

  谢谢老师，老师辛苦了。我现在才真正开始深入了解JAVA。 

   0

  回复

  2020-01-11

- [我最会吹牛比](http://www.imooc.com/u/6730629/articles)

  前面的都没看完 直接过来留言了 谢谢老师 写得很棒 哈哈 

   1

  回复

  2019-12-25

- [枫叶零渡](http://www.imooc.com/u/4136631/articles)

  前面的还没看完，先来看下最后一章，感谢老师 

   1

  回复

  2019-12-20

- [monkeyzi](http://www.imooc.com/u/3535380/articles)

  跟着老师的专栏和自己动手实践，这一遍也明白了不少东西，一定要坚持---致自己 最后感谢老师！加油！ 

   2

  回复

  2019-12-16

- [m113129](http://www.imooc.com/u/5696757/articles)

  加油！ 

   2

  回复

  2019-12-09

  - [文贺](http://www.imooc.com/u/8062574/articles)

    回复[m113129](http://www.imooc.com/u/5696757/articles)

    一起加油奋斗努力！！ 

    回复

    2019-12-16 17:48:10

- [dengweiqiang](http://www.imooc.com/u/1964095/articles)

  哈哈，最后一章就这么几个人留言么，有点小自豪啊 

   2

  回复

  2019-12-06

  - [文贺](http://www.imooc.com/u/8062574/articles)

    回复[dengweiqiang](http://www.imooc.com/u/1964095/articles)

    坚持到了最后，为你骄傲 

    回复

    2019-12-16 17:47:52

- [敲木鱼的小和尚](http://www.imooc.com/u/5761528/articles)

  老师，棒棒哒，之前看过源码，一些内容半知半解，看了老师的，每天做笔记看源码，懂了很多设计理念，设计模式，还有值得学习的地方，感谢老师 

   2

  回复

  2019-12-06

  - [文贺](http://www.imooc.com/u/8062574/articles)

    回复[敲木鱼的小和尚](http://www.imooc.com/u/5761528/articles)

    同学你也很棒，这么认真的同学很少了。 

    回复

    2019-12-08 13:31:45

- [weibo_可否争番一囗气_0](http://www.imooc.com/u/1188200/articles)

  希望出spring源码解读。 

   4

  回复

  2019-12-05

  - [大LOVE辉](http://www.imooc.com/u/2851044/articles)

    回复[weibo_可否争番一囗气_0](http://www.imooc.com/u/1188200/articles)

    +1+1+1+1+1+1+1+1+1+1 

    回复

    2019-12-06 13:12:32

- [所相虚妄](http://www.imooc.com/u/7839242/articles)

  谢谢老师 

   1

  回复

  2019-12-05

  - [文贺](http://www.imooc.com/u/8062574/articles)

    回复[所相虚妄](http://www.imooc.com/u/7839242/articles)

    也谢谢你哈，感谢你的支持和鼓励。 

    回复

    2019-12-08 13:32:18

- [慕码人6169125](http://www.imooc.com/u/6612138/articles)

  老师辛苦了！收货很大，respect 

   2

  回复

  2019-12-04

  - [文贺](http://www.imooc.com/u/8062574/articles)

    回复[慕码人6169125](http://www.imooc.com/u/6612138/articles)

    你有收获就是我最大的开心。 

    回复

    2019-12-08 13:33:09

  - [慕码人6169125](http://www.imooc.com/u/6612138/articles)

    回复

    [文贺](http://www.imooc.com/u/8062574/articles)

    老师会不会出一个Spring Boot的专栏呢？ 

    回复

    2019-12-08 14:41:10

- [前田慶次](http://www.imooc.com/u/5611237/articles)

  最后一章了，感觉老师讲的真心好。 

   2

  回复

  2019-12-04

  - [文贺](http://www.imooc.com/u/8062574/articles)

    回复[前田慶次](http://www.imooc.com/u/5611237/articles)

    谢谢，谢谢同学你一直以来陪伴和支持。 

    回复

    2019-12-08 13:33:31