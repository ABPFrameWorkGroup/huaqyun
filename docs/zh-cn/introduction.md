<!--
 * @Author: your name
 * @Date: 2020-03-20 10:39:00
 * @LastEditTime: 2020-03-20 14:55:37
 * @LastEditors: Please set LastEditors
 * @Description: In User Settings Edit
 * @FilePath: \Learing\web\huaqyun\docs\zh-cn\introduction.md
 -->
### 介绍

医信中台基于DDD的经典分层架构思想，实现了众多DDD的概念（但没有实现所有DDD的概念）。我们的目标是构建一个通用的，可适用于医疗行业软件开发的WEB应用程序基础框架和项目模板，以及整体的开发平台。医信中台最大的特点是可以跨平台部署，原生支持打包成Docker运行于Linux环境，或者Windows环境。兼容数据库，集成分布式消息队列，前后端分离架构，微服务化运行，可以将服务快速部署到任意的微服务架构中去，或者注册到servicesmesh（服务网格）中。

* 官方网站：[https://github.com/ABPFrameWorkGroup/AbpDocument2Chinese](AbpDocument2Chinese)
* 开源项目：[https://github.com/aspnetboilerplate](https://github.com/aspnetboilerplate)

### 服务器端
* .NET Core 3.0、C# 7.0
* DDD领域驱动设计 （Entities、Repositories、Domain Services、Domain Events、Application Services、DTOs等）
* autofac （依赖注入容器）
* EF CORE \ NHibernate，数据迁移
* Log4Net（日志记录）
* AutoMapper（实现Dto类与实体类的双向自动转换）

### 客户端
* vue-cli3.5.3、
* vue2.6.10,
* vue-router3.0.2、
* axios0.18.1、
* vuex3.1.0、
* eslint5.15.3

### 特性和功能
* 多语言/本地化支持
* 多租户支持（每个租户的数据自动隔离，业务模块开发者不需要在保存和查询数时写相应代码）
* 软删除支持（继承相应的基类或实现相应接口，会自动实现软删除）
* 统一的异常处理（应用层几乎不需要自己写异常处理代码）
* 数据有效性验证（Asp.NET MVC只能做到Action方法的参数验证，ABP实现了Application层方法的参数有效性验证）
* 日志记录（自动记录程序异常）
* 模块化开发（每个模块有独立的EF DbContext，可单独指定数据库）
* Repository仓储模式（已实现了Entity Framework、NHibernate、MangoDB、内存数据库）
* Unit Of Work工作单元模式（为应用层和仓储层的方法自动实现数据库事务）
* EventBus实现领域事件(Domain Events)
* DLL嵌入资源管理
* 通过Application Services自动创建Web Api层（不需要写ApiController层了）
* 自动创建Javascript 的代理层来更方便使用Web Api
* 封装一些Javascript 函数，更方便地使用ajax、消息框、通知组件、忙状态的遮罩层
* 身份验证与授权管理（通过ASP.NET Identity实现的）
* 用户&角色管理
* 系统设置存取管理（系统级、租户级、用户级，作用范围自动管理）
* 审计日志（自动记录每一次接口的调用者和参数）
### 适用的场景
* 中小规模WEB应用开发，可直接使用，较大型项目可以在框架的源码基础上进行扩展，以实现分布式架构。


