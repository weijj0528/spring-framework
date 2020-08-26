### Spring源码笔记

> Spring模块重多，如下图所示，其核心为IOC与AOP

![img](https://docs.spring.io/spring/docs/4.3.20.RELEASE/spring-framework-reference/htmlsingle/images/spring-overview.png)

#### 核心容器 IOC
1. 核心容器提供的功能

2. 核心容器包含以下模块

```
spring-core
spring-beans
spring-context
spring-context-support
and spring-expression
```
3. 如何使用

4. 需要了解的问题

- Bean初始化过程，在容器中的如何组织的
- Bean获取的过程，方式

#### AOP
1. AOP实现有功能
2. 包含哪些模块
```
spring-aop
spring-aspects
```
3. 基本使用
4. 需要了解的问题
- 哪些Bean会被代理
- 什么时候被代理的
