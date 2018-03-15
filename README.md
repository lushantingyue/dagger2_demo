## 依赖注入入门体验
基本概念: 依赖注入是面向对象的一种设计模式, 其目的是为了降低耦合, 这个耦合就是类之间依赖引起的.  <br> 
传统的注入依赖的方式: 接口实现, setter方法, 构造方法 都违反了单一职责原则和开闭原则. 
取而代之的, 我们使用Java注解的方式来 '注入依赖'
> 
[Dagger2 入门讲解](https://www.jianshu.com/p/22c397354997)


###  配置
    在modules/build.gradle 添加:
        implementation 'com.google.dagger:dagger:2.4'
        annotationProcessor 'com.google.dagger:dagger:2.4'

### 使用