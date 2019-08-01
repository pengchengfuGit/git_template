# Git提交模版

subject           用来简要描述本次改动,概述就好了,不能超过50个字符

body              具体的修改信息,应该尽量详细,每行不能超过72个字符
Reviewers         评审人
footer            放置写备注啥的,如果是Bug,可以把BugId放入
footer@bugId      Bug的Id

type的值可以有很多,下面有几个我们常用到的
type(feat)        新功能
type(fix)         修复Bug
type(doc)         文档改变
type(style)       代码格式改变
type(refactor)    某个已有功能重构
type(perf)        性能优化
type(test)        增加测试
type(build)       改变了build工具 如grunt换成了npm
type(revert)      撤销上一次的commit

scope:用来说明此次修改的影响范围 可以随便填写任何东西
scope(all)        表示影响面大,如修改了网络框架,会对整个程序产生影响
scope(location)   表示影响小,某个小小的功能
scope(module)     表示会影响某个模块 如登录模块,首页模块,用户管理模块等
