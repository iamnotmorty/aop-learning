# AOP-Learn
从实践的角度去学习AOP，本项目起始于用AOP实现自定义缓存时的各种思考，由此记录供温习学习使用。
<!-- TOC -->

- [AOP-Learn](#aop-learn)
    - [初始化Springboot项目](#初始化springboot项目)
    - [使用Redis实现缓存](#使用redis实现缓存)
        - [添加依赖](#添加依赖)
        - [添加配置](#添加配置)
        - [注解 @EnableCaching](#注解-enablecaching)
        - [注解 @Cacheable、@CacheEvict](#注解-cacheablecacheevict)
    - [自定义缓存注解](#自定义缓存注解)
        - [自定义 @MyCacheable 注解](#自定义-mycacheable-注解)
        - [基于 @Aspect 注解的缓存实现](#基于-aspect-注解的缓存实现)
    - [AOP的深入研究](#aop的深入研究)
        - [AOP相关名词](#aop相关名词)
        - [Spring AOP](#spring-aop)
        - [AspectJ](#aspectj)
    - [代理模式](#代理模式)
        - [静态代理](#静态代理)
        - [动态代理](#动态代理)
            - [JDK动态代理](#jdk动态代理)
            - [CGLib动态代理](#cglib动态代理)

<!-- /TOC -->
## 初始化Springboot项目
***
## 使用Redis实现缓存
### 添加依赖
### 添加配置
### 注解 @EnableCaching
### 注解 @Cacheable、@CacheEvict
***
## 自定义缓存注解
### 自定义 @MyCacheable 注解
### 基于 @Aspect 注解的缓存实现
***
## AOP的深入研究
### AOP相关名词
### Spring AOP
### AspectJ
***
## 代理模式
代理类代理委托类，客户端不直接调用委托类的目标方法，而是通过代理类间接的调用目标方法。
这种模式增加了客户端调用目标方法的间接性，正是这种间接性提供了在目标方法调用前后增加处理逻辑的空间。
> 注: 后续会用到Target（目标/委托类），Proxy（代理）
### 静态代理
### 动态代理
#### JDK动态代理
#### CGLib动态代理