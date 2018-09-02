# 团队架构和其他准备

经过考虑,这个任务需要一周内完成第一版, 负责该项目的小组成立了,

包括: 前端工程师(也就是我们), 后端工程师, 项目经理(梳理需求) , 和一位UI设计师同学.

大家的任务如下:

## 项目经理:

1. 负责梳理老板的需求, 形成文字
2. 负责把文字版的需求, 画成原型图, 给前后端工程师参考.
3. 每周的任务进度控制.
4. 承担测试人员的工作. 对已经完成的功能进行测试.

## 前端工程师

1. 负责呈现给用户使用的界面. 包括 H5端.
2. 负责与后端同学沟通API方面的问题

## 后端工程师

1. 负责后端管理员的操作界面
2. 负责给前端实现API接口
3. 负责数据库的设计, 实现等

## UI设计师

完成对于前端操作界面的设计.


## 要有个bug跟踪系统， 有个wiki

一定要有，但不要过分依赖。 我只用它做两件事： 

- bug跟踪： 记录每天要做的事
- wiki: 专门记录 前端 和 后端 所用到的API的格式. 

开源的redmine 很棒。 两者都满足。 如下图所示：

![redmine](/images/real_project/redmine.png)

## 要有个代码仓库

国外的github, 国内的 coding.net都很不错。 

对于初学者，最容易翻的错误就是不用版本控制。 同学们，一定记住，任何程序，都要用git保管起来。

对于目前的项目，需要两个，一个是h5端(shop_h5)， 一个是后台(shop_web)。