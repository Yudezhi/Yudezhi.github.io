---
layout: post
title: "浅括软件工程"
date: 2017-11-16
tags: 软件工程   
---
## 为什么写这篇博客

不知不觉，软件工程这门课已经结课了，也马上就要考试了，如果别人问自己什么是软件工程，想必可以说很多专业的名词来搪塞他，然而自己是骗不了自己的，我虽然可以背诵很多书上的定义，但是终究是觉得自己没有掌握其中真正的内涵。

因此，为了能够更进一步的让自己明白什么是软件工程，我在又看一遍书的基础上，准备强行让自己可以用一篇文章来讲述这本书的内容，一方面可以增强复习，加深理解，另一方面，也是对于这段时间的记录吧。也不算什么都没有留下。

## 软件工程的出现

软件工程提出的大背景就是在于计算机行业的快速发展下，硬件更新换代的速度加快，可以由于软件开发的特殊性，不能跟的上硬件的脚步，并且在日益复杂的软件开发项目中，开发变的举步维艰，并且错误百出。于是学术界，工业界等看不下去了，准备联合起来，认真分析其中的原理，搞出一套大家公认的“办事流程”出来，于是通过几次会议，就基本确定了软件工程。


## 自己眼中的软件工程

软件工程，其主要思想无非就是强调“三思而后行”。当然，在这里，思不仅仅是脑部活动，还需要开发人员参与一定的调查。具体是怎样“思”呢？思，一闪即逝，那么就是要求开发人员不断的整合各个过程的想法，问题，设计，形成各种阶段的文档。于是，就这样，渐渐的形成了共识，那就是文档也是软件开发的一部分。

软件开发是一项很大的工程，所以经过前人的经验总结，最后发现将一个工程进行阶段的划分，这样会在整个流程中更加的可控。而这其中的分阶段思想渐渐的也成为了软件工程的核心思想，那么将整个软件过程怎样划分呢？很自然的，真的，很自然的，就分成了 问题定义与可行性分析，需求分析，设计（概要设计，详细设计），测试，应用，维护。  可是就算这样分了，那么归根结底还是得到问题的解决上来，就像我们知道了很多道理，最后还是不知道怎样好好生活一样。可是，对待软件工程，为了克服不同开发人的人为因素，有了工程化的开发方法，总结成两种，就是结构化和面向对象的分析与设计。  说到这里，其实就已经说完了 软件工程生命方法学，在总结一下，就是分阶段，瀑布式，每个阶段的审查，采取结构化和面向对象的分析和设计。


## 软件工程生命周期


学习软件工程，先记住几个关键词： 软件生命周期，瀑布式，结构化分析与设计，面向对象的分析与设计



整个软件工程，或者说，一个严格的开发过程，确实有以下阶段：

`` 问题的分析和定义
   可行性研究
   需求分析
   概要设计
   详细设计
   编码实现
   测试
   应用
   维护 ``


在这里，我所提到的这些过程，不要过分纠结，可以将其中的部分几个合为一个。这些过程是一个完整的开发过程所必须的，有些是专门的阶段，需要严格的文档记录的，有些在潜移默化中已经完成了。

所以说，后面的学习，其实就是围绕这几个阶段进行学习，所以，也不枉叫做“软件工程”。

## 需求分析阶段
在需求分析阶段，我们主要得到的产物就是   软件需求规格说明书，在这其中的内容主要就是关于描述这个软件都有哪些必须的功能，大致是怎样的形式，就是形成一个初步的认识。那么在这其中，为了能够让不同的人写出来的规格说明书差不多，能让不同的人看，那么就有了一定的标准，最具有标志性的就是建模，建模主要有  数据建模，功能建模，行为建模，那么对应着的这个工具就是 ER图，dfd,std,判定树，判定表，pdl描述。关于这些工具，其实我们在平时的学习中，多多少少凭借着多年的学习生活经验早都用过，只是不太规范而已。这三种建模方式在这个阶段的是十分的重要。



说完上面的，我们已经利用工具完成了基本的分析，那么接下来就是实现，可是实现也不是说实现就可以的，所以先说一点看似废话的软件设计基本常识。模块化的设计想必大家早都耳熟能详，在这里就不多废话了，总之就是遵循“高内聚，低耦合”的原则就行，当然也不能太死板。高内聚最厉害的就是“功能内聚”，耦合追求的是数据耦合。

## 设计
好了，说完上面的，下面就是进入真正的设计了。  设计，又可以根据阶段分为“概要设计【总体设计】”和“详细设计”。下面分阶段说：
### 总体设计
概要设计【总体设计】：概要设计干的事情就是搞一个框架出来，也就是这个阶段，你要给上司画出一个蓝图来，怎么建，为什么，以后的施工怎么更好的结合等问题。  这设计根据不同的部分，又分为  结构设计，数据设计，接口设计，界面设计。  想必这几个设计大家都应该听说过，就不详细讲述了。  概要设计既然要想构建出软件的整体架构，那么枯燥的文字是不能完成这个艰巨的任务的，工具图是不可免的，这里用到的工具有   层次图和结构图，这样的图确实可以表示一些结构的整体框架。但是仅仅靠这两种图是不够的，还要依靠其他的方法，具体方法就是  事务流和变换流，经过这样的设计，我们得到的图结构更加的信息，逻辑信息也十分的清晰。两种方法在不同的数据流下有不同的特色。

### 详细设计
上面完成了软件的整体框架的搭建，下面就要真正的进入详细设计这一部分，其实这部分完成以后，我们的软件基本上就已经进入了成品阶段，因为在这一个阶段，需要完成每一个功能模块的实现设计，就是算法的具体实现，只不过不是代码，而是用伪代码等形式进行描述，而类似伪代码这种形式，就是在这个阶段所需要的工具，具体有  程序流程图，盒图，等。具体的运用方法自己查查就能够很快的知道。

## 实现
好了，详细设计完成了，那么就进入  实现阶段，这一阶段，就是根据详细设计说明书，看选什么程序语言进行具体的实现。


## 测试阶段
在实现之后，就是测试，这个阶段，相信你就算没有编码经验，也是可以理解的。  不过这里的测试就已经进行了方法的分类。 有“白盒”“黑盒”测试。  黑盒测试就是一直知道这个软件某些确定的输入和合法输出结果，然后不管中间是怎么运行的，就是测试结果是不是正确，然后得出结论，而白盒测试就是测试人员必须接触代码，看运行过程中的每一次代码运行是不是对的，是否在预期内。当然，真正的测试过程中还有更规范的操作，我这里只是随便说一下差不多的样子。 具体来讲，白盒需要测试代码结构中的每一个语句，每一条路径，每一个条件判断等，而黑盒需要进行一些边界值的测试，等价类的划分之类的方法。


测试完成后，原本上产品就可以运行，然后维护。但是上面的这些想法，工具，其实都离不开结构化的思想，我们不断的结构化，其中有些问题还是不能很好的解决。所以，，面向对象的方法运用而生。

## UML与面向对象
UML

UML翻译过来就是统一的建模语言，既然说了统一，那么肯定有一套完整的体系，各种统一的图形去建模，让开发人员和用户更好的了解软件。

UML一共有九种图，各有特色，用在不同的地方，只是为了让人更好的理解系统。UML无论其中究竟包含了哪些图，哪些关系，终究还是为了面向对象这个思想服务的，面向对象，根据目前的想法，就是将事物分类，然后根据类再定义对象，在类之间传递消息。 不过，这一块，思想的精髓我承认我没有抓到。所以就不说了。


上面，基本上就完成了一个软件的开发，其中涵盖软件开发开始前的准备，中间做事的思想，做事的工具，做事的准则。

## 维护阶段

 那么，后面这一部分就是要说，无论怎样努力，我们都会犯错，人终究是不能敌不过时间的局限，所以需要“维护阶段”。  维护阶段其实可以根据不同的情况有不同的维护，比如因为自己开发过程中的疏忽而产生的隐形错误，后期运行过程中渐渐的出现，这时就需要 纠错性维护。再比如时代发展太快，自己曾经的产品现在跟不上时代，不适应一些情况了，那么就需要“适应性维护”，再比如产品使用过程中，有了新的需求，那么需要”“完善性维护”，当然，还有你觉得未来可能会出现什么样的问题，提前要维护，就叫”“预防性维护”。

当然，维护不一定总是好的，有时候新的维护，恐怕是解决了一个旧问题，引入十个新问题，就像校园网一样，越是维护，越是垃圾一样。

好了，以上就是一般的软件工程所牵扯的内容，由于时间关系，关于语言的组织，排版等都没有做，只是将文字素材放在这里，提醒我还有一个坑要填。