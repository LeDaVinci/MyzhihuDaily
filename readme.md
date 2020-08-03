# 仿知乎日报练习
### 前言
最近看了RxJava和Retrofit和kotlin，光看看写点小demo不够过瘾啊，所以就选了个合适的项目练下手。
因为之前就想写个仿知乎日报的应用来着（其实我最想搞个聊天应用出来玩玩的，相对来说工作量有点大）。

### 自动化配置
| 仓库 | 构建 | 测试覆盖率 |
| --- | --- | --- |
| master | [![Build Status](https://travis-ci.org/LeDaVinci/MyzhihuDaily.svg?branch=master)](https://travis-ci.org/LeDaVinci/MyzhihuDaily)| [![codecov](https://codecov.io/gh/LeDaVinci/MyzhihuDaily/branch/master/graph/badge.svg)](https://codecov.io/gh/LeDaVinci/MyzhihuDaily) |

### 知乎日报API
在github上发现有位前辈专门把知乎日报的的内容拉取到自己的中转并且公开了API，所以就用这个，非常nice，毕竟我自己也不会弄这个。[API地址](https://github.com/iKrelve/KuaiHu/blob/master/%E7%9F%A5%E4%B9%8E%E6%97%A5%E6%8A%A5API.md)