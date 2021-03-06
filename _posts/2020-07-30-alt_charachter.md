---
layout: post     
title:  天不生我Alt，键道万古如长夜      
category: 天不生我Alt，键道万古如长夜  
copyright: python                           
tagline: by 轩辕御龙       
tags: 
  - 
---

# 天不生我Alt，键道万古如长夜

众所周知，阿酱人缘很好，路子很野。可谓是朋友遍天下（用词夸张，记得删掉）。

可是前几天跟人聊天的时候却差点没被气死……

让我们见证一下现场：

<!--more-->

![01](http://www.justdopython.com/assets/images/2020/07/30/01.png)

我……？

有没有感受到一种嘲讽？一种轻蔑和不屑，就这样淡淡地流露出来，透过眼前的显示器，把公屏打在了尴尬上。

就仿佛是这样两个表情的合体：

![02](http://www.justdopython.com/assets/images/2020/07/30/02.png)

![03](http://www.justdopython.com/assets/images/2020/07/30/03.png)

好尴尬呀，好尴尬呀，怎么办？在线等。

悄悄是别离的笙箫，沉默是今晚的康桥。

但我不能沉默！

我要搞清楚他到底是怎么输入的这个字符！

（因为我找了半天，在手机的特殊字符里也没找到这个字符）

## 日常忽视的Alt

说起来，我们日常用的键盘上有三个比较特殊的按键：Shift，Ctrl和Alt。

前两者都不用说了，用处很广。尤其是对程序员来说，按住Shift可以临时切换大小写，放开又恢复；Ctrl-C+Ctrl-V就更不用说了，这是多少猿们吃饭的家伙。

倒是第三个Alt，存在感不强，通常也就是要么用QQ截图的快捷键Ctrl-Alt-A，要么切换窗口按Alt-Tab，才会想起这位小兄弟。

啊扯远了，先说这里。

阿酱这个人你知道的，好奇心重得不得了。当下就拿这个问题问了发出“¿”符号的老哥。

老哥告诉我按住Alt键，然后\*\*\*\*\*\*\*\*\*\*\*\*（此处加密）。

现在坐在电脑前的朋友们跟我一起操作。

首先按住电脑键盘上的Alt键（左右都没关系，按一个就好），然后在键盘右边的小键盘上依次按下数字1、9、1，松开Alt键。

![04](http://www.justdopython.com/assets/images/2020/07/30/04.png)

到这里，大家应该都得到了¿这个倒问号。如果还不行，把你旁边的人打一顿就好了。

此时嗅觉敏锐的阿酱顿时意识到不对：小键盘？闻到了阴谋、啊不，字符编码的味道。

奈何当时手头一无电脑，二无字符编码表，所以只能之后尝试了。

## 快手字符

咳咳，先声明啊，这个“快手”和那个“快手”没有任何关系，非要说有关系可能就是在字面意思上有关系。因此此处不收取广告费。

这里“快手”指的是速度很快，快手字符就是说可以很快输入一些特殊字符，单身三十年的手速都比不上那种快。

所谓“天下武功，无坚不摧，唯快不破”，当你掌握了这么一门必杀技，何愁不能驰骋对话框，纵意WeChat？没错，说的就是你，这位键客。

Alt-191是¿，接下来我们自然而然就会想到Alt加别的数字是什么呢？也是字符吗？

我记得大写字母A的字符编码是61，试一试：=。

什么鬼？

啊哈，8好意思8好意思，A的编码是65，61是小a的十六进制编码（-  -#）。再来：A。

啊舒服了。

再来。192：À。155：›。233：é。235：ë。54698：摘。54699：斋。

看来猜测没错，Alt加数字可以输入字符的原理就是字符编码了。

汉字都可以通过这种方式输入。兄台若是有雅兴，不妨背下全部汉字的编码。没别的，就图个装X。

实际上，查询资料我们可以清楚地知道，Alt和数字组合输入字符时，“数字”就是对应字符的十进制编码。

不过要注意的是，这里的编码并不是咱们熟悉的（至少是听说过的）UTF-8字符编码，而是对应于电脑本地的字符映射。

比较可以发现

这里有一个办法查看本地的字符映射：在Win10左下角的搜索框中输入“字符”，即可看到这样的入口：

![05](http://www.justdopython.com/assets/images/2020/07/30/05.png)

回车即可打开。

这里就可以查看本地的字符编码啦~

所以只要记住最常用的几个字符编码，就可以在聊天的时候快速输入，绝不拖泥带水了。

当然，其只要实记住191就好了。

兵贵精不贵多，一个¿足矣。

![06](http://www.justdopython.com/assets/images/2020/07/30/06.gif)

阿酱现在要活学活用，先去挑衅一下老板了（连夜提桶跑路）。

![07](http://www.justdopython.com/assets/images/2020/07/30/07.png)

## 总结

今天教了大家一个快速挨打的好方法，大家都学会了吗？有什么想法在评论里说说吧~

（是不是有内味了）

> 示例代码：无