###  :tw-1f310: 去中心化应用型公链 :tw-1f310: 

OC（OnlyChain）系统，提出最大兼容全领域商业应用的区块链生态系统架构，旨在实现去中心化应用和半中心化应用的数据兼容和性能扩展。该系统架构搭建后，将有组织的协调分布式计算机为应用提供服务，其中基础层包含对数以百计处理器、内存、硬盘、带宽、接口的调度使用，通过智能合约将一系列去中心化的核心业务在链上高效的协同运转工作，OC系统深度优化集群技术，在应用业务上，每秒可处理海量数据。通过节点面版集成生态应用插件，在丰富生态应用的同时，助力企业和开发者以更低门槛构建自己事业。OnlyChain 是一套可兼容并能快速处理去中心化与半中心化应用的高性能区块链应用生态系统，深度结合指数型组织的成功商业模式，建立更加高效、完善的应用生态。

 **1、数据结构** 
在OC系统中采用和以太坊相似的MPT数据结构,在该版本中增加系统TOKEN锁仓的结构支持

 **2、共识机制** 
OC系统采用 BFT-DPOS 共识体系，依靠该共识算法防止出现生产节点之间的作恶和分叉风险，保障生产出的区块100%安全可靠。

 **2.1 BFT** 
在原有的BFT算法上进行改进，这里称为改进型BFT算法。由于PBFT算法不适用投票系统，恶意节点很容易操控局势，让一部分节点以为出块成功，另一部分节点以为出块失败，从而导致出块节点受到惩罚，网络不佳的情况下也可能发生这种情况，且效率欠佳。
改进型BFT算法流程如图：
![image](https://images.gitee.com/uploads/images/2020/0627/151311_07728aa7_459087.jpeg "bft.jpg")
