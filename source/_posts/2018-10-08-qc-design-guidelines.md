---
layout:     post
title:      青橙Web端设计规范1.0设计总结
excerpt: 记一次造轮子的经历

category:	Projects
tag:
  - Blog
photos: https://raw.githubusercontent.com/CloverTuan/Markdown_Images/master/web-guidelines/guidelines-cover.png
---

> 设计规范是一套有规则的标准，同时提供了可变化的设计方法，方便迭代、方便其他人进行设计。它的存在不是为了约束我们的发挥，反而是让我们把精力放在更有价值的地方。

## 项目背景
前段时间我们启动了Web端设计规范这个项目，一方面是为了优化系统的用户体验，另一方面则是为了提高整个团队的工作效率和产出质量。完整的项目展示可以在这里观看：[On Behance](https://www.behance.net/gallery/71573697/Web10) | [On Zcool](https://www.zcool.com.cn/work/ZMzEyMDc4MzY=.html)

**主要价值**

设计规范主要是对产品中的一些可通用的交互方式、视觉样式、组件等进行规范化，它的价值有以下几点：

![](https://raw.githubusercontent.com/CloverTuan/Markdown_Images/master/web-guidelines/guidelines-1.png)

**为什么不用别人的轮子？**

现在已经有一些很成熟的前端组件库可以直接使用了，如Element、Ant Design 等，我们为什么不直接用呢？主要是因为我们使用的前端框架和它们不同，如果要迁移的话成本很大，因此我们只能自己做个轮子了。

## 我的角色
作为这个项目的负责人及推动者，我的工作内容主要包括以下几点：

* 制定项目的目标、实施步骤及产出结果
* 产出设计规范的内容
* 在团队内部推广和使用设计规范
* 设计规范后续的维护和迭代

我们团队的人力并不富足，在这个项目中只有我和一名前端工程师参与进来，且并没有一个完整的项目周期让我们去做这件事，也就是说我们要在日常业务项目之余花时间去完成它，在这样的情况下，从开始到最后投入使用，我们差不多花了两个月的时间，将投入成本和对公司其他项目的影响降到了最低。

## 设计步骤

![](https://raw.githubusercontent.com/CloverTuan/Markdown_Images/master/web-guidelines/guidelines-10.jpg)

## 产出内容
设计规范使用对象不仅限于设计师，还包括前端工程师、产品经理等，不同角色的需求是不同的。

![](https://raw.githubusercontent.com/CloverTuan/Markdown_Images/master/web-guidelines/guidelines-3.png)

根据上面的分析，最终确定此次产出的内容及呈现形式分别是：

![](https://raw.githubusercontent.com/CloverTuan/Markdown_Images/master/web-guidelines/guidelines-4.png)

## 交互 + 视觉的规范文档
规范文档不是一份仅包含视觉样式的文档，除了组件外，还包括系统里的通用交互规范、文档信息等。

![](https://raw.githubusercontent.com/CloverTuan/Markdown_Images/master/web-guidelines/guidelines-5.jpg)

**通用交互规范**

通用交互规范主要是一些文字说明，用来规范系统里一些细小的、容易被忽略的问题，避免体验的缺失或体验不统一，如下图。

![](https://raw.githubusercontent.com/CloverTuan/Markdown_Images/master/web-guidelines/guidelines-8.jpg)

**组件规范**

每个组件的规范，除了组件的视觉样式外，还要给出该组件的交互方式、使用场景说明，让阅读文档的人能够明白这个组件是怎样使用的，必要的时候还可以给出正确示例和错误示例。以按钮组件为例，规范中需要包含系统中出现的所有按钮，以及各自的使用场景和注意事项，如下图。

![](https://raw.githubusercontent.com/CloverTuan/Markdown_Images/master/web-guidelines/qcguidelines-7.png)

## UI Kit
以 Sketch Library 的形式呈现，在 Sketch 中引用即可，为了便于后续的维护和迭代，这里把颜色、icon、组件做了拆分，如下。

![](https://raw.githubusercontent.com/CloverTuan/Markdown_Images/master/web-guidelines/guidelines-6.jpg)

## 前端组件库 [clover-ui](https://qingchengfed.github.io/angular-clover-ui/) 

由于时间有限，因此在设计的后半段，前端工程师就开始开发了，且大多是利用下班后的时间做的，在此要感谢前端小熊同学的支持。有趣的是，小熊同学以我的名字命名了这个UI框架，线上查看[ clover-ui ](https://qingchengfed.github.io/angular-clover-ui/)。有了设计规范和这个组件库后，一些简单的页面已经不需要设计师再出设计稿了，可以说大大解放了劳动力。

![](https://raw.githubusercontent.com/CloverTuan/Markdown_Images/master/web-guidelines/guidelines-7.png)

## 更多设计展示

完整的项目展示可以在这里观看：[On Behance](https://www.behance.net/gallery/71573697/Web10) | [On Zcool](https://www.zcool.com.cn/work/ZMzEyMDc4MzY=.html)

![](https://raw.githubusercontent.com/CloverTuan/Markdown_Images/master/web-guidelines/qcguidelines-2.png)
![](https://raw.githubusercontent.com/CloverTuan/Markdown_Images/master/web-guidelines/qcguidelines-3.png)
![](https://raw.githubusercontent.com/CloverTuan/Markdown_Images/master/web-guidelines/qcguidelines-4.png)
![](https://raw.githubusercontent.com/CloverTuan/Markdown_Images/master/web-guidelines/qcguidelines-5.png)
![](https://raw.githubusercontent.com/CloverTuan/Markdown_Images/master/web-guidelines/qcguidelines-6.png)
![](https://raw.githubusercontent.com/CloverTuan/Markdown_Images/master/web-guidelines/qcguidelines-7.png)
![](https://raw.githubusercontent.com/CloverTuan/Markdown_Images/master/web-guidelines/qcguidelines-8.png)
![](https://raw.githubusercontent.com/CloverTuan/Markdown_Images/master/web-guidelines/qcguidelines-9.png)
![](https://raw.githubusercontent.com/CloverTuan/Markdown_Images/master/web-guidelines/qcguidelines-10.png)
![](https://raw.githubusercontent.com/CloverTuan/Markdown_Images/master/web-guidelines/qcguidelines-11.png)
![](https://raw.githubusercontent.com/CloverTuan/Markdown_Images/master/web-guidelines/qcguidelines-12.png)
![](https://raw.githubusercontent.com/CloverTuan/Markdown_Images/master/web-guidelines/qcguidelines-13.png)

## 推行、使用及迭代
**1）在团队中推行设计规范**

不要以为产出一份打着「设计规范1.0」的文档就算结束了，其实这才是刚刚开始。接下来要解决的问题是如何在团队内推行规范，并保证规范的落实。以下是我们确定的方案：

![](https://raw.githubusercontent.com/CloverTuan/Markdown_Images/master/web-guidelines/guidelines-12.png)

交互自查表如下:

![](https://raw.githubusercontent.com/CloverTuan/Markdown_Images/master/web-guidelines/guidelines-13.jpg)

**2）在项目中使用规范**

对于整个系统，我们没办法整体一次性替换修改，只能对组件进行替换，同时保证以后的新功能迭代按照新的规范来设计开发。具体我们是怎么根据这套规范来改版系统的，可以阅读这篇文章：[组件化的运用—健身房管理系统Web改版小结](http://clovertuan.github.io/2017/11/07/qcweb/)

**3）维护和迭代**

在后期的使用过程中，需要对规范进行维护和迭代，并保证实时更新给大家，当发现系统需要用到新的组件或者原有组件有问题、不完善、不是最优时，可以设计或补充新的解决方案，添加到规范里，并广而告之。这时就体现组件化的优势了，可以很快地全局更新某一个组件，效率高、成本低。

以日历选择器的组件为例，之前只考虑到了选日期的操作，但上线使用后，选择会员出生年月时就很麻烦，发现这个问题后，我们把它优化成了既可以选择日期，也可以根据键盘输入来匹配日期。

![](https://raw.githubusercontent.com/CloverTuan/Markdown_Images/master/web-guidelines/guidelines-11.png)

## 遇到的困难
**1）资源有限**

公司主要以业务为导向，且人力资源有限，这件在我看来优先级很高的事情，在公司的层面优先级并不高，能给的资源不多。因此我们大多是利用项目外时间、甚至是下班后的时间做的，很感谢项目成员的理解与支持。

**2）忽视规范 & 刻板遵守**

在规范的使用过程中，我发现很容易出现两种极端的问题：

* 似是而非：使用功能、交互与现有组件完全相同，但视觉有些许差异的组件
* 生搬硬套：有些组件并不适用于当前的业务场景，但还是照搬不误

这两个问题刚好是两个极端，一个忽视规范的存在，自由发挥；另一个则又掉入了刻板遵守规范的泥潭。我鼓励设计师们去完善去优化这套规范，如果觉得这个组件不好用、不好看、不能满足需求，我们可以一起去改，而不是放飞自我或者压抑自己。为了解决这个问题，我们在后期加强了设计师之间的 review 流程。

## 总结
严格意义上来说，这算是一个我真正完全独立负责的项目，从项目开始落地到最终的上线使用，我不只是单纯地扮演一个设计师的角色，也是整个项目的负责人和推动者，很开心这套规范最终能够投入使用并取得了不错的效果。以下是我的一些经验总结。

**1）如果可以，不要重复造轮子**

虽然很开心能有这样的机会做一套相对完整的设计规范，但如果有下一次的话，还是希望我们的开发团队在技术上能够选用如 Element、Ant Design 这样现成的前端框架，避免重复造轮子。无论从完整度还是从设计质量、代码质量来讲，这些框架肯定比我们的更扎实，毕竟是大厂耗费了许多资源开发维护、并且已经得到很多验证的。这样不仅可以提高效率，还可以让我们把更多的时间放在业务思考上。对于一个 SaaS 系统来讲，业务和服务才是我们应该专注的特色，稳定和高效才是我们追求的目标。

**2）设计师也应关注自上而下的项目流程**

多关注项目流程，知道自己的设计方案是怎样被使用的，知道自己在团队中所处的位置，才能知道自己可以做到什么程度。设计师在团队中的价值绝不仅仅是那几张图几个页面而已，自身价值的最大化就是团队价值的最大化。

**3）规范既不是用来约束创造力，也不是用来刻板地套用的**

规范的存在是为了让大家将精力放在更有价值的地方。在这套规范投入使用后，我跟大家最常说的一句话就是：如果你们发现里面有不合理的、不完善的地方，或者你们有更好的解决方案的时候，一定要提出来，大家一起优化，一定不要为了遵循它而去套用不合适的组件。引用电影「变形金刚」的特效导演 Alex Jaeger 的一段话：

> 很多人认为最厉害的设计来源于天马行空的想象，但其实它们来源于在各种条条框框的限制下，你能做出什么？任何人都能在那么大的盒子里做设计，但是现在你的盒子只有这么小，你能设计出什么？

设计规范就个条条框框的存在，但我希望，除了遵守之外，大家也有质疑这个条条框框的能力和决心！

