# Acknowledgements
## 定义
### DDD
Domain-Driven Design，领域驱动开发。是一种指导复杂软件开发的方法论。

许多项目做了建模的工作，但是最后却没有获取到实际的益处。DDD提炼出了一些有效的、从细节到全局的实践经验。

DDD并非独立的、全新的理论，而是吸收了软件开发过程中诞生的诸多不错的思想，最终的目的即是帮助更好地建模。

DDD主要有以下特点：
1. 聚焦于core domain
2. 通过领域专家与软件开发者协同进行model的探索
3. 在指定的bounded context中使用ubiquitous language

### domain
知识、影响、活动相关的领域。
### model
domain某一方面的抽象，用于描述及解决domain此方面的相关问题。将业务知识提炼成一系统清晰的概念即是建模。
### context & bounded context
context是指决定术语（包括model等）、陈述含义的一个范围。bounded context是指这个context是有界限/边界的，并通常以此边界来划分子系统、Team。
一个系统难免有多个model，为了避免因model较多而产生混乱，采用bounded context对多个model进行收纳限定。
### ubiquitous language
在一个bounded context中，被一个团队所统一使用的术语。包括开发人员之间的统一，也包括开发人员与领域专家之间的统一。
model的抽象也是在开发人员和领域专家共同讨论下完成的，在这一过程中形成了统一语言，因此统一语言的变化往往伴随着model的调整。
![](../images/ubiquitousLanguage.png)

#### domain VS context
#### 界限上下文如何确定
1. 团队/组织
2. 物理层面的隔离，比如代码库、数据库

![pattern-language-overview](../images/pattern-language-overview.png)

### Continuous Integration
当多名成员在一个界限上下文中工作时，model都会有着碎片化的趋势，因此采用持续集成减少每次变化的量以及时发现问题。

## DDD落地相关技术
CQRS与Event Sourcing是DDD中比较主流的架构选择。
Qi4j、Naked Objects、Roo虽然并未那么普及，但也有比较重要的意义。

## 相关书籍
The big Blue Book: 《Domain-Driven Design, Tackling Complexity in the Heart of Software》 - 2004

The big Red Book: 《Implementing Domain Driven Design》 - 2013

《DDD with Naked Objects》
