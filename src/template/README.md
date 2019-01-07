# 模板模式

说白了就是子类重写父类的方法。

> **优点：** 1、封装不变部分，扩展可变部分。 2、提取公共代码，便于维护。 3、行为由父类控制，子类实现。
>
> **缺点：** 每一个不同的实现都需要一个子类来实现，导致类的个数增加，使得系统更加庞大。

父类写好大部分公共方法，子类去做出差异化调整。

和建造者模式的区别大概在于：
1. 建造者模式顶层是接口
2. 模板模式顶层是抽象类
3. 建造者模式每个 Builder 的方法内部逻辑基本不同，而模板模式是基本相同局部不同
