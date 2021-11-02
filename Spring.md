# Spring

---

**大概步骤**

+ 加载xml -> 解析xml -> 封装（BeanDefinition） -> 实例化 -> 放在容器中 ->  从容器总获取

**BeanFactory 和 FactoryBean 的区别**
BeanFactory 是个工厂，是 IOC 容器，提供了容器最基础的功能和约束；而 FactoryBean 是个工厂 Bean，能生产或者修饰对象生成的工厂 Bean，它的实现与工厂模式和修饰器模式类似。

**Bean 的实例化过程**

![img](https://img-blog.csdnimg.cn/20210510144229675.png)

**Bean 的生命周期**

