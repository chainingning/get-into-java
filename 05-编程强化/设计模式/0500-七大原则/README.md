# README

7个常用的面向对象设计原则

现在相信你已经了解了基础的设计模式，那就让我们来看看名为 SOLID 的五条原则吧。这五条原则是在罗伯特·马丁的著作《敏捷软件开发：原则、模式与实践1》中首次提出的。SOLID 是让软件设计更易于理解、更加灵活和更易于维护的五个原则的简称。

与生活中所有事情一样，盲目遵守这些原则可能会弊大于利。在程序架构中应用这些原则可能会使其变得过于复杂。我对
于是否真的有能够同时应用所有这五条原则的成功软件产品表示怀疑。有原则是件好事，但是也要时刻从实用的角度来考量，不要把这里的每句话当作放之四海皆准的教条。 

开闭原则是核心！！！！！

| 设计原则名称          | Design Principle                                             | 定义                                                         | 使用频率 |
| --------------------- | ------------------------------------------------------------ | :----------------------------------------------------------- | -------- |
| **单一职责原则(SRP)** | [Single Responsibility Principle](01-single-responsibility-principle.md) | 一个对象应该只包含单一的职责，并且该职责被完整的封装在一个类中 | ★★★★☆    |
| **开闭原则(OCP)**     | [Open Closed Principle](02-open-closed-principle.md)         | 软件实体应该对拓展开放，对修改关闭                           | ★★★★★    |
| **里氏代换原则(LSP)** | [Liskov Substitution principle](03-liskov-substitution-principle.md) | 所有引用基类的地方必须能透明地使用其子类的对象               | ★★★★★    |
| **依赖倒转原则(DIP)** | [Dependence Inversion Principle](04-dependence-inversion-principle.md) | 程序要依赖抽象(抽象类或者接口)而不是具体的实现,从而降低用户与实现模块的耦合度 | ★★★★★    |
| **接口隔离原则(ISP)** | [Interface Segregation Principle](05-interface-segregation-principle.md) | 客户端不应该依赖那些他不需要的接口                           | ★★☆☆☆    |
| **合成复用原则(CRP)** | [Composite Reuse Principle](06-composite-reuse-principle.md) | 优先使用对象组合，而不是继承(聚合)来达到复用的目的           | ★★★★☆    |
| **迪米特法则(LoD)**   | [Law of Demeter](07-law-of-demeter.md)                       | 每一个软件单位对其他的单位都只有最少的知识，而且局限于哪些于本单位密切相关的软件单位 | ★★★☆☆    |

