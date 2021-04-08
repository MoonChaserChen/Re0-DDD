# Acknowledgements
## 定义
### DDD
Domain-Driven Design，领域驱动开发。是一种指导复杂软件开发的方法论。

许多项目做了建模的工作，但是最后却没有获取到实际的益处。DDD提炼出了一些有效的、从细节到全局的实践经验。

DDD主要有以下特点：
1. 聚焦于core domain
2. 通过领域专家与软件开发者协同进行model的探索
3. 在指定的bounded context中使用ubiquitous language

### domain
知识、影响、活动相关的领域。
### model
domain某一方面的抽象，用于描述及解决domain此方面的相关问题。
### context & bounded context
context是指决定术语（包括model等）、陈述含义的一个范围。bounded context是指这个context是有界限/边界的，并通常以此边界来划分子系统、Team。
### ubiquitous language
在一个bounded context中，被一个团队所统一使用的术语。

## DDD落地相关技术
1. CQRS
2. Event Sourcing
3. Qi4j
4. Naked Objects -> 书籍：DDD with Naked Objects
5. Roo


## 相关书籍
The big Blue Book: 《Domain-Driven Design, Tackling Complexity in the Heart of Software》
The big Red Book: 《Implementing Domain Driven Design》
《DDD with Naked Objects》