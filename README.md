## muduo-copy（just for learning）

 [![license](https://img.shields.io/github/license/mashape/apistatus.svg)](https://opensource.org/licenses/MIT)

#### 起因

2019年秋招的时候做过一个高并发服务器的项目[Slack](https://github.com/plantree/Slack)，明眼人都知道是仿照着陈硕老师的[muduo](https://github.com/chenshuo/muduo/tree/master/muduo/)网络库。那本书，《Linux多线程服务端编程》翻来翻去也看过好几遍，东西虽然学的囫囵吞枣，但是对于整个秋招的帮助还是很大的，起码心里有底。

一年过去了，逐渐走上工作岗位，。东西忘的差不多，其他的开源项目都比较大，多少有些畏难情绪。上手的话还是选择一个简单的项目，积累点自信，后面打算看看Redis、LevelDB等，这是后话。

所以考虑把muduo仿照着再实现一遍，而且中间的这段时间，muduo项目内部也有了一些新的变化，当然核心功能不变。

#### 工具

- cmake，项目管理
- catch，单元测试
- Travis CI，持续集成

