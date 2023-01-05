# 本周 PyDev:Vasudev Ram

> 原文：<https://www.blog.pythonlibrary.org/2015/05/18/pydev-of-the-week-vasudev-ram/>

本周我们欢迎 Vasudev Ram ( [@vasudevram](http://twitter.com/vasudevram) )成为我们本周的 PyDev。瓦苏德夫是一名[自由开发者](http://www.dancingbison.com)，他[在很多不同的软件主题上写博客](http://jugad2.blogspot.com)，包括 [Python]( http://jugad2.blogspot.com/search/label/python) 。他是 [xtopdf](https://bitbucket.org/vasudevram/xtopdf) 的创作者，你可以在这里阅读更多关于[的内容。让我们花些时间去更好地了解他吧！](http://slides.com/vasudevram/xtopdf)

你能告诉我们一些关于你自己的情况吗(爱好、教育等)

当然可以。我在印度工作，目前是一名独立的软件顾问，曾在美国和印度的多家公司工作多年。音乐(各种流派，包括西方和印度)，徒步旅行是我的一些爱好。

我在大学学的是数学。我在高中 12 年级开始接触计算机，通过许多人都有的途径:在许多品牌的个人计算机上学习。

一天，一个学校的朋友(一个电子爱好者)向我展示了一台卡西欧袖珍电脑，里面有 BASIC 语言的只读存储器。它带有一个手册和示例程序。它甚至有一个 4 线图形液晶显示器。

我对这个新设备很感兴趣，向他借了几天。我用它玩了一圈，写了许多程序——像算术计算、统计、字符串操作、简单的游戏和图形——有数学/物理/逻辑背景的人可能会尝试编程的常见事物。这就是我对编程感兴趣的原因。(后来在许多不同类型的计算机和一些不同的操作系统上工作过——许多 UNIX 版本，包括基于 PC 的和更高端的，还有 Windows——在早期，还有 DOS 和 Netware。)

然后在我的大学时代，我参加了许多计算机课程，关于编程语言和其他主题；还在我感兴趣的各个领域做了很多编程，包括数学、图形、声音等。

大学毕业后开始做程序员。实际上，一开始我是一名自由职业者，参与了几个小而有趣的项目，使用 dBASE III 和 Turbo Pascal(这两种工具在当时都非常流行，也是相当强大的工具。)然后加入了一个小软件之家做程序员。(后来成长为系统分析师、项目经理等角色。在印度和美国的大公司，这些年来参与了各种各样的项目，并且在各种基础软件主题上得到了很好的培训；我现在又成了一名开发人员，回到了几年前的自由职业咨询公司。)在我职业生涯的早期，在 UNIX 上做过很多 C 编程和 shell 脚本。从中我学到了很多系统层面的东西，这对我的职业生涯很有帮助。此外，我一直对系统级工作以及工具和实用程序的开发感兴趣。在 IBM developerWorks 上发表了一篇主题为“开发 Linux 命令行实用程序”的文章——参见下面的链接一节。

就公司而言，在我的职业生涯中，我曾为各种公司工作或提供咨询，无论是大公司还是小公司、印度公司还是美国公司、企业还是初创公司。由于我工作过的公司种类繁多，角色各异，我接触了许多不同的技术和业务领域。我也做过一些软件产品(相对于咨询项目)，包括在一个成功的 C 语言中间件产品中担任团队领导，我的 xtopdf 产品有一些用户。我接触过的行业领域包括:软件和数据库设计、项目管理、配置管理和良好的软件工程实践，以及 UNIX 系统管理。我曾经有一点 UNIX 管理的天赋，作为一名系统工程师在现场工作(随叫随到),除了日常的管理工作之外，还在早期为我的雇主——一家大型 UNIX 供应商的客户解决了许多棘手的问题；在那个阶段获得的系统优势和故障排除技能对我的整个职业生涯都有帮助)

我从所有这些经历中学到了不同的东西，包括什么有效，什么无效，我还在学习🙂

**你为什么开始使用 Python？**

几年前，在网上看到一些文章后，我开始学习 Python，最初是作为一种爱好。当时我正在专业地研究 Java 和 C 语言。我发现 Python 非常可读和高效，你知道——“可执行伪代码”，当然还有“包括电池”的东西，尽管它现在比我开始时有更多的库，而且版本也更高；我想当时大概是 1.5 左右吧。随着时间的推移，我开始在自由职业者的咨询项目中使用它，也因为它的高级性质，开始使用它来构建一些项目/产品想法的原型，并且它经常证明原型足够好，足以成为最终产品——从某种意义上说，不需要为了性能或其他原因而用另一种语言重写它。

你还知道哪些编程语言，你最喜欢哪一种？

至少在某种程度上，我喜欢我所学习和使用的大多数语言。你可以从你学习的每一种语言中学到一些东西。但是回答你的问题，大致按时间顺序，从早到晚:

Turbo Pascal 非常有趣——在我职业生涯的初期，我经常使用它。这在当时是一个不可思议的环境——一个快得惊人的编译器(就像 Turbo C 和后来的 Delphi)和不到 40KB 的编辑器，是的，K，而不是 m。在工作中做了许多 UNIX C，有些是为了好玩，早期的 Turbo C 也是，也很好玩，用 Turbo C 和 Turbo Pascal 做了许多基本的图形编程；在一段时间内，Borland tools 几乎是终极产品(对我来说);Java，在工作中，更早，也很好；我喜欢 Servlet 的优雅，这是我很早就开始研究的，在 J2EE 出现之前，虽然 JSP——不太喜欢，直到今天，Jason Hunter 的 Java Servlet 编程(第一版)仍然是我最喜欢的编程书籍之一——我认为写得非常好。然后在. com 项目中使用 Ruby(和 Rails ),几年来，在 web 和非 web 工作以及我自己的开源项目中使用了大量 Python。在我的职业生涯中，我几乎一直在使用 SQL(在各种关系数据库中，包括私有的和开源的)和 shell (sh/ksh/bash 以及 sed 和 awk 等朋友)。我也做过一些 Visual Basic，用于现实生活中的项目和小工具，我喜欢它(和 Delphi 一样)是因为它的 GUI 应用程序开发速度，尽管我对 VB 语法不太感兴趣。

我没有一个最喜欢的，但是 Python 可能是第一个——暂时是——因为它的生产力、可读性、社区性、用户友好性和它的大量库(尽管和所有语言和工具一样，它也有它的问题)。我想是 Dennis Ritchie 被问到，如果他被困在一个荒岛上，只有一种编程语言，他会想要哪一种，他说 C。我可能会想要 Python 和 C。我最喜欢的其他语言是 C (evergreen)和 Delphi(尽管 Delphi 更像是一个完整的开发环境，而不仅仅是一种语言)。我之前在里面写过几个小工具。虽然不是这方面的专家。

Ruby 也很有趣。我是 Ruby 的早期用户，我喜欢它比 Python 更注重面向对象，但我不是语言律师，所以不要引用我的话:)。最近没怎么用，虽然前一段时间很擅长。我也偶尔涉猎其他语言，在空闲时间，出于兴趣和学习其他做事方式。通过 Franz 的 Allegro CL 和 LispWorks 的工具，我尝试了一下 Lisp(也叫 Scheme ),阅读了 Peter Seibel 的一些实用的 Common Lisp 和一些其他 Lisp 书籍，并且喜欢上了这门语言。对于任何对新/旧/另类语言感兴趣的人来说，我在过去检查过的一些语言包括 Pike、Elastic、Icon 等等。

你现在在做什么项目？

除了经常涉及 Python、Linux 和数据库(针对 web 或非 web 应用程序)的专业咨询工作，我一直致力于 xtopdf(参见:[http://slides.com/vasudevram/xtopdf](http://slides.com/vasudevram/xtopdf))和其他一些产品创意。我在我的博客上宣布我的新产品发布/版本:[http://jugad2.blogspot.com](http://jugad2.blogspot.com)

任何感兴趣的人都可以随意订阅它的[提要](http://jugad2.blogspot.com/search/label/python)，或者由 Python 帖子组成的子集。

哪些 Python 库是你最喜欢的(核心或第三方)？

就像语言一样，有许多种。xtopdf 是我自己的用于 pdf 创建的 Python 库。它建立在 ReportLab 的基础上，为 ReportLab 的功能子集提供了一些更高级别的抽象。这是我喜欢做的一件事。不知何故，我一直在为它寻找新的应用/用途。

我认为这与我最初开发它时应用了一些约束有关，从某种意义上说，我没有试图成为每个人的一切，或者有太多的功能(至少一开始是这样)。也许结果是，我发现它与许多其他库是正交的(我喜欢这个词和概念),并且可以很好地与许多其他库一起使用——就像 UNIX 哲学(创建小工具，做好一件事),这可能影响了我，因为我在 UNIX 上工作了很多。这里不得不提的是，ReportLab 的工作人员做得非常出色。在其他库中，我喜欢 XML-RPC(轻量级分布式计算)的简单性，Python 中有针对它的客户端和服务器库，我还研究了同一领域的其他一些技术，如 PYRO 和 RPyC。DB API，当然是面包和黄油之类的东西。SQLAlchemy。喜欢 PyDAL，最近发现的。它就像 SQLAlchemy 核心 ORM 本身下面的一层。wxPython，requests，json，一些 XML 库。csv，tablib(最近看到的)-作为一个喜欢数据管理的人。我喜欢时不时地去看看与互联网、网络和多媒体相关的图书馆。我继续探索新的库——事实上，我博客上的许多帖子都是关于我遇到的新 Python 库，然后编写演示程序来展示/探索如何使用它们；参见:

[http://jugad2.blogspot.com/search/label/python](http://jugad2.blogspot.com/search/label/python)

**你还有什么事吗？我想说什么？**

是的。感谢邀请我参加这个系列！我一直在阅读该系列的其他帖子；它们很有趣。我想提一下，我是你博客的读者，在那里发现了许多好文章。最后，我发现你是经常在 IRC 频道#wxpython(昵称 driscollis)上闲逛的人，很多人，包括我，都发现你在上面的回答很有帮助。谢谢！

非常感谢！

### 一周的最后 10 个 PyDevs

*   [朱利安·丹朱](https://www.blog.pythonlibrary.org/2015/05/11/pydev-of-the-week-julien-danjou/)
*   马特·哈里森
*   阿迪娜·豪
*   [诺亚礼物](https://www.blog.pythonlibrary.org/2015/04/20/pydev-of-the-week-noah-gift/)
*   道格拉斯·斯塔内斯
*   [可降解的脊椎动物](https://www.blog.pythonlibrary.org/2015/04/06/pydev-of-the-week-lennart-regebro/)
*   迈克·弗莱彻
*   丹尼尔·格林菲尔德
*   伊莱·本德斯基
*   [Ned Batchelder](https://www.blog.pythonlibrary.org/2015/03/09/pydev-of-the-week-ned-batchelder/)