---
title: 为什么学习JavaScript？
layout: page
category: introduction
date: 2012-12-29
modifiedOn: 2014-01-09
---

每当我开始阅读一本很厚的书，总是先问自己，它值得我这样做吗？

读完一本书，就像完成一段旅程。有些旅程会让你终身回忆，而另一些旅程让你后悔不迭，不应该将宝贵的生命浪费在它之上。

所以我想，在读者开始阅读这本教程之前，我最好也谈谈为什么要学JavaScript，它有什么用？一方面，我不希望有人因为读了我的书而后悔；另一方面，这本教程的厚度也许让人望而生畏，有些部分相对枯燥，还有些部分并不容易掌握，如果你清楚地知道阅读的目的，将会比较容易坚持下去。当然，我可以保证，虽然这本教程很厚，但是没有废话，讲的都是有用的东西。

总的来说，JavaScript语言有一些显著特点，使得它非常值得学习。它既适合当作学习编程的入门语言，也适合当作日常开发的工作语言。它是目前最有希望、前途最光明的计算机语言之一。

## 操控浏览器的能力

JavaScript的发明目的，就是作为浏览器的内置脚本语言，为网页开发者提供操控浏览器的能力。它是目前唯一一种通用的浏览器脚本语言，所有主流浏览器全部支持。它可以让网页呈现各种特殊效果，为用户提供良好的互动体验。

目前，全世界大部分网页都使用JavaScript。如果不用，网站的易用性和使用效率将大打折扣，无法成为操作便利、对用户友好的网站。

对于一个互联网开发者来说，如果你想提供漂亮的网页、令用户满意的上网体验、各种基于浏览器的便捷功能、前后端之间紧密高效的联系，JavaScript是必不可少的工具。

## 广泛的使用领域

近年来，JavaScript的使用范围，慢慢超越了浏览器，正在向通用的系统语言发展。

**（1）浏览器的平台化**

随着HTML 5的出现，浏览器本身的功能越来越强，不再仅仅能浏览网页，而是越来越像一个平台，JavaScript因此得以调用许多系统功能，比如操作本地文件、操作图片、调用摄像头和麦克风等等。这使得JavaScript可以完成许多以前无法想象的事情。

**（2）Node.js**

Node.js项目使得JavaScript可以用于开发服务器端的大型项目，网站的前后端都用JavaScript开发已经成为了现实。有些嵌入式平台（Raspberry Pi）能够安装Node.js，于是JavaScript就能为这些平台开发应用程序。

**（3）数据库操作**

JavaScript甚至也可以用来操作数据库。NoSQL数据库这个概念，本身就是在JSON（JavaScript Object Notation，JavaScript对象表示法）格式的基础上诞生的，大部分NoSQL数据库允许JavaScript直接操作。基于SQL语言的开源数据库PostgreSQL支持JavaScript作为操作语言，可以部分取代SQL查询语言。

**（4）跨移动平台**

PhoneGap项目使得JavaScript可以开发在多种移动平台（iOS和Android）上使用的应用程序。Mozilla基金会的手机操作系统Firefox OS，更是直接将JavaScript作为操作系统的平台语言。

**（5）内嵌脚本语言**

越来越多的应用程序，将JavaScript作为内嵌的脚本语言，比如Adobe公司的著名PDF阅读器Acrobat、Linux桌面环境GNOME 3。

**（6）跨平台的桌面应用程序** 

Chromium OS、Windows 8等操作系统直接支持JavaScript编写应用程序。Mozilla的Open Web Apps项目、Google的[Chrome App项目](http://developer.chrome.com/apps/about_apps)、以及[TideSDK项目](http://www.tidesdk.org/)，可以用来编写运行于Windows、Mac OS和Android等多个桌面平台的程序，不依赖浏览器。

**（7）小结**

可以预期，JavaScript最终将能让你只用一种语言，就开发出适应不同平台（包括桌面端、服务器端、手机端）的程序。根据2013年9月的[统计](http://adambard.com/blog/top-github-languages-for-2013-so-far/)，JavaScript是本年度代码托管网站Github上使用量排名第一的语言。

著名程序员Jeff Atwood甚至提出了一条[“Atwood定律”](http://www.codinghorror.com/blog/2007/07/the-principle-of-least-power.html)：

> “所有可以用JavaScript编写的程序，最终都会出现JavaScript的版本。”(Any application that can be written in JavaScript will eventually be written in JavaScript.)

## 易学性

相比学习其他语言，学习JavaScript有一些有利条件。

**（1）学习环境无处不在。**

只要有浏览器，就能运行JavaScript程序；只要有文本编辑器，就能编写JavaScript程序。这意味着，几乎所有电脑都原生提供JavaScript学习环境，不用另行安装复杂的IDE（集成开发环境）和编译器。

**（2）简单性。**

相比其他脚本语言（比如Python或Ruby），JavaScript的语法相对简单一些，本身的语法特性并不是特别多。而且，那些语法中的复杂部分，也不是必需要学会。你完全可以只用简单命令，完成大部分的操作。

**（3）与主流语言的相似性。**

JavaScript的语法很类似C/C++和Java，如果学过这些语言（事实上大多数学校都教），JavaScript的入门会非常容易。

必须说明的是，虽然核心语法不难，但是JavaScript的复杂性体现在另外两个方面。

首先，它涉及大量的外部API。JavaScript要发挥作用，必须与其他组件配合，这些外部组件五花八门，数量极其庞大，几乎涉及网络应用的各个方面，掌握它们绝非易事。

其次，JavaScript语言有一些设计缺陷。某些地方相当不合理，另一些地方则会出现怪异的运行结果。学习JavaScript，很大一部分时间是用来搞清楚哪些地方有陷阱。Douglas Crockford写过一本有名的书，名字就叫[《JavaScript: The Good Parts》](http://javascript.crockford.com/)，言下之意就是这门语言不好的地方很多，必须写一本书才能讲清楚。另外一些程序员则感到，为了更合理地编写JavaScript程序，就不能用JavaScript来写，而必须发明新的语言，比如CoffeeScript、TypeScript、Dart这些新语言的发明目的，多多少少都有这个因素。

尽管如此，目前看来，JavaScript的地位还是无法动摇。加之，语言标准的快速进化，使得JavaScript功能日益增强，而语法缺陷和怪异之处得到了弥补。所以，JavaScript还是值得学习，况且它的入门真的不难。

## 强大的性能

JavaScript的性能优势体现在以下方面。

**（1）灵活的语法，表达力强。**

JavaScript既支持类似C语言清晰的过程式编程，也支持灵活的函数式编程。可以用来写并发处理（concurrent）。这些语法特性已经被证明非常强大，可以用于许多场合，尤其适用非同步编程。

JavaScript的所有值都是对象，这为程序员提供了灵活性和便利性。因为你可以很方便地、按照需要随时创造数据结构，不用进行麻烦的预定义。

JavaScript的标准还在快速进化中，并不断合理化，并添加更适用的语法特性。

**（2）支持编译运行。**

JavaScript语言本身，虽然是一种解释型语言，但是在现代浏览器中，JavaScript都是编译后运行。程序会被高度优化，运行效率接近二进制程序。而且，JavaScript引擎正在快速发展，性能将越来越好。

**（3）事件驱动和非阻塞式设计。**

JavaScript程序可以采用事件驱动（event-driven）和非阻塞式（non-blocking）设计，在服务器端适合高并发环境，普通的硬件就可以承受很大的访问量。

## 开放性

JavaScript是一种开放的语言。它的标准是国际标准，写得非常详尽明确；主要的设计和实现都是开放的，而且质量很高；不属于任何公司或个人，不存在版权和专利的问题。

行业内的主要公司都支持它，单单是解释器就有好几个品种，兼容性很好，不做调整或只做很小的调整，它编写的程序就能在所有浏览器上运行。

## 社区支持

全世界程序员都在使用JavaScript，它有着极大的社区、广泛的文献和图书、丰富的代码资源。绝大部分你需要用到的功能，都有多个开源函数库可供选用。

作为项目负责人，你不难招聘到数量众多的JavaScript程序员；作为开发者，你也不难找到一份JavaScript的工作。

