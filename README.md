# conversation-dsl

the conversation program language which make it easier to write logic code with python.

## 

昨天[Huan](https://www.github.com/huan)在群里面分享了如下的对话流程设计语言，具体案例如下所示：

[![](./assets/image/csml.png)](https://www.csml.dev/)

我看后非常的激动，因为我觉得这么简洁的对话设计语言，其实python也是可以实现的，于是简单写了一下基于python的类似对话流程设计代码，如下所示：

![](./assets/image/carbon.svg)

从技术的角度上来讲，其实是可以实现的，具体的做法可以通过AST来对设计代码进行重新编译，实现最后的代码运行。

目前遇到的难点：

* 对话设计如何保存每一个event 状态，并能够返回到此状态下？
* hold是在等待用户的回复，如何对其进行编译？


## Creators

- [@wj-Mcat](https://github.com/wj-Mcat) - Jingjing WU (吴京京)

## Copyright & License

- Code & Docs © [@wj-Mcat](https://github.com/wj-Mcat)
- Code released under the Apache-2.0 License
- Docs released under Creative Commons
