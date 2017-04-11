# 写给白帽子的数据科学手册
Yarning about data science for white hat security researchers
`https://github.com/phunterlau/data_science_for_whitehat`

请到 gitbook 阅读 [`https://www.gitbook.com/book/phunterlau/data-science-for-whitehat/details`](https://www.gitbook.com/book/phunterlau/data-science-for-whitehat/details)

一个想法，希望能够达成，为白帽子的技能树加上数据科学的分支。

我在和很多白帽子安全研究员交谈中发现，越来越多的安全类业务项目和研究方向需要数据和机器学习的介入，而从传统白帽子培养路线走过来的白帽子缺乏数据分析和建模方面的训练，导致他们在学习和利用数据及机器方法的时候有起步的困难。同时，很多朋友在为公司寻找懂安全研究的数据科学家来建立数据相关安全项目组，他们花费了很多努力但是很难找到合适人选。我想整理编写一个简单的手册，从我对安全方向的理解总结出一些白帽子们必须学习的数据科学知识，帮助白帽子们快速补充需要的数据知识，消除对数据和机器学习的恐惧感，最重要的是培养数据科学模型的思想，从而快速学习和探索安全领域里的数据方法。我相信白帽子都十分聪明，这个小手册可以帮大家快速热身。

我想按照这样的结构安排：先快速补充基础知识，再谈谈常见的数据分析方法，并针对安全领域的特性介绍和领域相关的机器学习知识和应用数据科学方法论。我并不想把这本手册做成涵盖全面的教科书，而是考虑过拟合（overfit）到安全领域需要的知识，所以不要太指望这是一本包打天下的数据科学圣经。同时我也相信白帽子读者都是智力在常人之上的，所以这本手册也不会浪费篇幅推导描述聪明人一看就懂的内容来假装内容丰富，而是以实际安全业务例子切入介绍相关知识点，仅在关键问题和步骤上详细说明，并给出简单的练习题和深入阅读指南。请读者朋友一定要做习题来练习巩固知识，并根据手册提到的内容自己酌情拓展深入学习展开自己的技能树，这才是懂了道理也能过好一生的办法。我希望提供一个给聪明人的快速学习方法。

以下是我设想的大纲，可能随着时间和写作进度修改。

基础知识

* 矩阵和基本线性代数
* 基本概率论
	* 排列和组合
	* 贝叶斯概率
* 基本离散数学建模方法
* 图论和常见图模型方法

数据分析方法

* 假设检验方法

机器学习

* 统计机器学习概述
* 常见监督学习建模方法
* 聚类方法和其他非监督学习方法
* 异常检测
* 序列建模的深度学习

应用数据科学方法论

* 规则系统、统计系统和数据系统
* 白帽子和数据科学家的合作方法

特别感谢

[@beader](https://github.com/beader) 教我用了 `gitbook` 确实好用