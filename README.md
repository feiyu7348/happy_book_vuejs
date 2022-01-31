# 说明

本书版本为 2.x, 本在线教程的内容属于"精简版",比实体书的内容少一些. 欢迎大家购买：https://item.jd.com/12517946.html

实体书的[勘误表在这里](errors_in_book.md) .   (在此,向各位读者致以歉意)

本书3.x 版本已经收尾，敬请期待!

## 对于本书2.x版本的代码demo

1. 不包含最后一章的demo: https://github.com/sg552/happy_book_vuejs
2. 最后一章的前端demo:  https://github.com/sg552/vuejs_book_demo_frontend
3. 最后一章的后端demo:  https://github.com/sg552/vuejs_book_demo_backend

## 对于本书3.x 版本的demo

合计有3个demo:

1. 不包含最后一章的demo:  https://github.com/sg552/vue3_lesson_demo
2. 最后一章的前端demo: https://github.com/sg552/vue3_lesson_demo
3. 最后一章的后端demo: https://github.com/sg552/vuejs_book_demo_backend


# 本书缘起

这个教程，是根据我公司过去2016年-2018年的实际项目经验写的。

我从2016年经营自己的软件公司。 到2018年6月，我们做了近三十个项目。 这些项目中，对于手机端的web的呼声很高。
大部分都要求在手机端使用web打开。

在使用Vuejs之前， 我考察过Angular（包括1.x, 2.x 版本)， React，Meteor，这几个框架都不行。

要么是学习曲线陡峭，概念复杂，把简单的事情复杂化（例如Angular），

要么就是编码风格不好，前后端代码混写一起，（例如React, Meteor)


而Vuejs是当时在stackoverflow等国外技术站点上被一致看好的技术。

第一次使用是在2016年4月。 Vuejs 1.x的时候。 我们发现入门特别快，稍微有一定web开发经验的程序员，在一周内就可以上手做项目，
认真学习的话，一个月就可以达到熟手水平（快速的开发项目）， 两三个月左右就可以达到高级水平（熟练使用Vuex, 自己写component等）

这么快的上手速度，在其他语言中是不可想象的。 根据我的实际体会， 使用Angular 入门需要一个月。 使用React入门速度也没有这么快。

总之，越是简洁的框架，就越好学。

后来我们在项目中使用它，一发不可收拾。 只要是个h5项目，就可以很好的用起来。 快速开发，快速迭代，性能杠杠的。

而且，额外的好处，是可以非常好的跟Native App的开发结合。在IOS上可以做到完美呈现， 让人无法分辨哪个页面是原生，哪个页面是H5做的。

## 学习目标

本教程是我公司的员工培训教程，可以在极短的时间内(例如一周)让人上手Vuejs项目。 让人：

1. 看得懂代码
2. 可以写一些基本的功能
3. 可以调试, 部署

这就算入门H5开发了。

## 使用说明

如果世界上文档分成两类：

- guide, 教程型文档。
- api, 接口型文档.

本文档就是入门的教程型文档。 在线查看地址：http://vue_book.siwei.me/

本教程的代码，都来源于这个demo:  https://github.com/sg552/vue_js_lesson_demo

以及： code_example 目录。

本书使用gitbook写就，可以自行编译, (安装环境和编译命令，参考：http://siwei.me/blog/posts/gitbook-gitbook)

本书中的出现的命令行，都统一以 `$` 作为开始， 例如：

```
$ npm install vue-cli
```

各位对命令行不熟悉的同学，记得在敲命令的时候，跳过最前面的 `$` 即可.

## 版本说明

截止到2016年6月底， Vuejs的版本是 `2.5.16`. 本书中的大部分例子都是在该版本下演示的。

如果您是一名没有任何工作经验的新人，在windows 环境下，建议使用 sublime(免费) + git bash (免费) ，就可以运行本书中的所有例子了。

如果您是一名有工作经验的老鸟，那么Linux, Mac则是非常好的选择~

那么，我们开始一段的令人兴奋的学习历程吧！
