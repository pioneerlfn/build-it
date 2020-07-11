# 引言
这篇笔记📒主要包括两部分:
1. 如何构建things/tools,    
2. How does it work

两部分的风格可能有重叠，区别在于第一部分有完整的代码实现
<br>而第二部分主要侧重于原理或过程讲解。


## Part 1: How to build it
A collection of posts that teach people how to build useful things/tools


|link| language| Depth| 吐槽|
|---|---|---| --- |
| [Writing an OS in Rust ](https://os.phil-opp.com/) | Rust|☆☆☆☆☆| 谁还没有过精通OS的梦呢 |
|[build a sqlite from scratch](https://cstack.github.io/db_tutorial/) | C |☆☆☆☆|
|[Implementing Raft](https://eli.thegreenplace.net/2020/implementing-raft-part-0-introduction/) | Go| ☆☆☆| paper读完了么？<br>看一下怎么实现它 |
|[用Go实现一个基于AST的数学表达式计算引擎](https://www.yoytang.com/math-expression-engine.html) | Go|☆☆|
|[Matching regexes using backtracking](https://marcin-chwedczuk.github.io/matching-regexes-using-backtracking) | Java|☆☆|
|[Building a high performance JSON parser](https://dave.cheney.net/high-performance-json.html) | Go| ☆☆| 零内存开辟 |
| [用 Go 构建一个区块链](https://ethfans.org/posts/building-blockchain-in-go-part-1)|Go| ☆☆| 比上一个长完备很多，适合兴趣更浓厚的朋友 |
| [用 Python 撸一个区块链](https://mp.weixin.qq.com/s/qTw_WELfVZCGIjxTXy4aBA) | Python| ☆ | 一个demo区块链<br>还没入门的小白可以看下 |


## Part 2: How it works
> ☆☆☆☆☆ 代表对的学习帮助很大，因此极力安利的内容

|link|type|推荐指数|吐槽|
|--- |---|---|---|
|[How does a relational database work](http://coding-geek.com/how-databases-work/) |Text| ☆☆☆☆☆ | 菜鸟与你的差距，可能就在于他没读过这篇长文|
|[On learning InnoDB: A journey to the core](https://blog.jcole.us/2013/01/02/on-learning-innodb-a-journey-to-the-core/)|Text|☆☆☆☆☆|通过阅读这个系列<br>我对引擎的理解登堂入室|
|[[译] Linux 网络栈监控和调优：接收数据（2016)](http://arthurchiao.art/blog/tuning-stack-rx-zh/)|Text|☆☆☆☆| 对理解linux网络栈很有帮助|
|[Let's talk locks!](https://www.youtube.com/watch?v=tjpncm3xTTc&t=619s)|Video|☆☆☆| Kavya Joshi 小姐姐的Tech Talk<br>对我理解 *mutex, atomic, spinlock, futex* 等很基础重要的概念帮助很大 |
| [以太坊的工作原理](https://mp.weixin.qq.com/s?__biz=MzIwODA3NDI5MA==&mid=2652525172&idx=1&sn=6adc7246269da5b939c0d60d1ca6b3dd&chksm=8ce65129bb91d83f6f3c77f9c4eb753a9fd729ca1923ae19b3c89b430ad29c3139f9dfdc6883&mpshare=1&scene=1&srcid=0402BRttslZ9sFTvpTCvUFEW#rd) |Text| ☆☆| 想了解以太坊的可以看下这篇 |