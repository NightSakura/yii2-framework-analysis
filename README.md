# Yii源码分析
Yii是一个高性能，基于组件的PHP框架，用于快速开发现代Web应用程序。 名字Yii（读作易）在中文里有“极致简单与不断演变”两重含义， 也可看作 Yes It Is! 的缩写。Yii 是一个通用的 Web 编程框架，即可以用于开发各种用 PHP 构建的 Web 应用。 因为基于组件的框架结构和设计精巧的缓存支持，它特别适合开发大型应用。

Yii2.0是面向现代PHP技术进行完全重写的版本，采用了最新的技术和协议，包括依赖包管理器 Composer、PHP 代码规范 PSR、命名空间、Traits（特质）等等。本系列主要就Yii的核心代码进行分析，目前我也将添加注释的代码提交到Git，该项目是通过`composer create-project --prefer-dist yiisoft/yii2-app-basic basic`指令生成的。

## 运行流程
* [框架运行流程](yii.md)
* []()

## 控制反转
* [DI容器](analysis/DI.md)
