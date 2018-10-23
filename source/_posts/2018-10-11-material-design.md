---
layout:     post
title:      Material Design 新知
excerpt: 在 Google I/O 2018 大会上，Google 设计团队发布了他们最新的 Material Design 成果，抽空通读了一下官方文档，对Material Design 有了一些新的认识...


category:	UI/UX
tags:
  - Blog
photos: https://raw.githubusercontent.com/CloverTuan/Markdown_Images/master/material-design/md-cover.jpg

---

在 Google I/O 2018 大会上，Google 设计团队发布了他们最新的 Material Design 成果，抽空通读了一下[官方文档](https://material.io/design)，对 Material Design 有了一些新的认识，可以说是很惊喜了，原来用 Material Design 也能创造出这么多奇妙的产品，不再是刻板地硬搬设计规范。你能想象以下这些产品都来自 Material Design 吗？

![](https://raw.githubusercontent.com/CloverTuan/Markdown_Images/master/material-design/md1.jpg)

如果说之前的 Material Design 是教我们如何用这套 **设计规范** 将自己的产品「Material Design 化」，那么 Material Design 2018 则是告诉我们怎样用这款 **设计语言** 去系统化地设计产品、思考设计方案。其中给我印象最深的是以下几点：

* Brand Expression：强调设计与品牌的结合度，而不是一味地套用规范和组件库
* Customize：根据品牌特性定制化字体、颜色、组件等
* Material Studies：基于 Material Design 的设计案例库，值得反复学习
* Material Theme Editor：强大的 Material Design 设计插件

## Brand Expression

很多学习过 Material Design 的同学，一提到 Material Design，浮现在脑海的大概都是卡片、圆角、厚重的阴影、悬浮的圆形按钮、侧滑抽屉等等。虽然有一些基于 Material Design 的设计案例，不论是线上的产品还是设计师的redesign，但大多都是类似的模式，像是给产品硬套上一个 Material Design 的外壳，而产品自己的品牌特色却湮没在这个外壳里，做来做去都像是Google家的产品，而忽略了品牌本身。

![](https://raw.githubusercontent.com/CloverTuan/Markdown_Images/master/material-design/brand-expression-1.jpg)
▲ 从左至右依次是：Google Play、Fabulous、Wally、Relay

Material Design 2018 里无数次强调 Brand expression，在布局、色彩、字体排版、形状、图标等各个维度都强调 **设计与品牌的结合度**。给出的几个设计案例也都特色鲜明，不再是千篇一律的样子，谁说卡片一定要是圆角？谁说一定要有投影？谁说一定要用Roboto？... **产品中所有字体、色彩、图形、形状的选择都不是生搬硬套的，它们应当是为品牌和内容服务的。**我们需要跳出那些固定模式。

在看的时候这一点给了我很大启发，即便不使用 Material Design，这套思维一样是适用的。在很多时候，我们的脑子里都塞满了很多固定模式，也被很多优秀设计「洗脑」过，在做设计时会有一些惯性，但这些惯性却不一定是合适的。在做设计时，不妨多问问自己几个问题：

* 你的品牌风格是什么？你的产品想要传达出什么样的感觉？
* 你选择的字体、色彩、图标、形状跟你要传达的感觉一致吗？
* 除了那些 default 选项，是否有更合适的选择？
* 你沾沾自喜地用在产品里的那些流行的、大火的设计元素跟你的品牌是否相符？你是否正在生搬硬套？
* 有没有可能在产品里加入一些 Branding moment ?

在官方给出的设计案例 [Material studies](https://material.io/design/material-studies/about-our-material-studies.html) 里，每个产品都风格鲜明，配色、字体、图标、形状等都非常契合整体风格，而且产品里都有一些非常动人的「Branding moment」，正是因为有了这些 moment，「品牌」才得以在繁重的产品中透透气。

▼ 新闻类产品[ Fortnightly ](https://material.io/design/material-studies/fortnightly.html)，整体比较简洁，以信息呈现为主，打造沉浸式的阅读体验。简洁归简洁，品牌信息却不能因此完全省略掉，这里通过logo、字体排版、颜色等表达。

![](https://raw.githubusercontent.com/CloverTuan/Markdown_Images/master/material-design/brand-expression-3.jpg)

▼ 时尚电商产品[ Shrine ](https://material.io/design/material-studies/shrine.html)，以女性为主要用户，在配色上很符合产品的气质，同时在界面里多处运用到 logo 中的元素：多边形、尖角、斜切角等。

![](https://raw.githubusercontent.com/CloverTuan/Markdown_Images/master/material-design/brand-expression-2.jpg)

## Customize
Material Design 2018 的 Principle 里增加了一条 Customize，即定制化、个性化。来看看[官方文档](https://material.io/design/introduction/#principles)里对这一条是怎么解释的：

> Customize: Expand Material’s visual language and provide a flexible foundation for innovation and brand expression.

即扩展 Material Design 的视觉语言，为创新和品牌表达提供一个灵活的基础。说人话就是可以根据需要修改视觉。这与上面说的 Brand Expression 是相辅相成的，品牌需要通过可定制化的视觉语言去表达，定制化则需要根据品牌特性来进行。

主要通过定制颜色、字体、图标、组件、动效等来实现个性化，同时 Google 在 Develop 层面也做了很多优化和修改，方便在代码层面实现定制化（否则设计师这么改的话大概要被开发追着跑）。

下面是[ Material studies ](https://material.io/design/material-studies/about-our-material-studies.html)里的一些定制化对比图：

![](https://raw.githubusercontent.com/CloverTuan/Markdown_Images/master/material-design/customize-1.jpg)

## Material Studies
[Material studies ](https://material.io/design/material-studies/about-our-material-studies.html)这一部分是最让我惊喜的了，最初就是从这一部分开始看的，看完之后只有一个想法：原来 Material Design 还能做出这样的产品来。Google 应该也是想要这个结果的吧！

Material studies 是一个基于 Material Design 的设计案例库，里面包含7个设计案例，分别涵盖娱乐、电商、新闻、办公等多个领域，向我们展现各种不同功能、不同风格的产品在 Material Design 下可以有怎样的解决方案。每个案例都会展示整体设计思路，从设计与品牌的结合度、信息架构、布局、色彩、字体排版、图标、组件、动效等维度分析，让我们看到结果之外的设计过程，可以说是满满的干货，值得反复学习。

看了这些案例分析，让我对设计过程和思考方式有了更多的了解，带来了很多启发。以后不论是自己做设计还是看别人的产品，用这样的思路去分析也是不错的方式。这个部分我应该还会二刷吧，也许下一次看又会有不一样的收获。

这里面给我印象最深的是[ Basil ](https://material.io/design/material-studies/basil.html)和[ Shrine ](https://material.io/design/material-studies/shrine.html)这两个产品，一个将字体排版发挥到极致，另一个则将品牌元素与shape融合得非常好。稍稍有点遗憾的是，这些都只是设计案例，没办法下载下来在手机上真正体验一下。

▼ Basil：一款菜谱应用，将字体排版发挥到极致。

![](https://raw.githubusercontent.com/CloverTuan/Markdown_Images/master/material-design/material-study-1.jpg)

▼ Shrine：一款电商应用，将品牌元素与shape融合得非常好。

![](https://raw.githubusercontent.com/CloverTuan/Markdown_Images/master/material-design/material-study-2.jpg)

## Material Theme Editor
此次 Google 还配套出了一款工具：sketch 插件[「Material Theme Editor」](https://material.io/tools/theme-editor/)。它能够在 Sketch 中快速生成基于 Material Design 的设计规范，并且能够按照需求自定义组件样式、全局替换，大大提高设计师的工作效率。来看看它能够做到哪些自定义的内容：

**1 颜色**

通过定义设计规范里的主色、次级色、背景色等等，全局替换相关组件里的颜色，而且可以检查颜色的对比度来满足可视性需求。

![](https://raw.githubusercontent.com/CloverTuan/Markdown_Images/master/material-design/mte-1.jpg)

**2 形状**

Material Design 2018 里，[Shape](https://material.io/design/shape/about-shape.html) 除了可以是直角、圆角外，还可以有斜切、凹陷的形式。选择形状的类型并设置参数后，可以全局应用到所有相关的组件中，实现形状的定制化。

![](https://raw.githubusercontent.com/CloverTuan/Markdown_Images/master/material-design/mte-2.jpg)

**3 字体**

能够设置默认字体类型，并且可以基于 Material 的字体排版规范来自动调整字体大小及自重来保证可读性，最多可以添加3中默认字体，且可以直接使用 Google 家的很多字体。

![](https://raw.githubusercontent.com/CloverTuan/Markdown_Images/master/material-design/mte-3.jpg)

**4 图标**

预置了5种类型的图标：填充型、尖角型、圆角型、轮廓型以及双色型图标，后4种都是这次新加入的，你可以根据产品的风格选择相应的图标。

![](https://raw.githubusercontent.com/CloverTuan/Markdown_Images/master/material-design/mte-4.jpg)

## 其他
还有一些很小的点，但还是想说说：

* Shape：在 Material Foundation 里专门加了一节来讲[ Shape ](https://material.io/design/shape/about-shape.html)，即形状。它除了之前的直角、圆角外，还可以有斜切、凹陷、多边形的形式。和字体、图标、颜色一样，形状也可以作为表达手段，它可以用来表达元素的状态，也可以和字体、颜色结合使用来建立品牌的视觉语言。在某些程度上为我们打开了思路。
* Backdrop：增加了[ Backdrop ](https://material.io/design/components/backdrop.html#)组件，包含前景内容层和背景操作层，比较适合用于以筛选为主要功能的页面。
* FAB：此次对 Material 中最典型的[ FAB ](https://material.io/design/components/buttons-floating-action-button.html)也做了扩展，FAB 可以定制成不同的形状和大小。

## 最后
相比之前的版本，这次 Google 的设计文档可以说是新增了很多内容了，完全啃下来真的很需要时间，但还是建议小伙伴们一定要读一读，绝对有收获。因为它已经不是一个简单的方便你遵守和快速使用的规范和组件库了，而是一个系统化的设计语言，向你展示更为合理的设计过程与设计思路。**规范和组件库应当是为我所用，而不是让我去刻板地遵守的。**期待后面看到更多基于此的优秀设计！

附：[Material Foundation 思维导图](https://raw.githubusercontent.com/CloverTuan/Markdown_Images/master/material-design/Material%20Design%20Part2-Material%20Foundation.jpg)

