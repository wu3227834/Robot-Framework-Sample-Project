Robot Framework Tutorial
========================

A Complete Example
------------------
http://blog.codecentric.de/en/2012/04/robot-framework-tutorial-a-complete-example/

Code structure - AI
------------------
SampleLibrary - 自定义Java关键字库

类型: Java项目，用于创建Robot Framework关键字库

主要文件:

- SampleKeywordLibrary.java: 核心关键字库实现
- 使用Stack<String>数据结构实现栈操作相关的关键字
- 构建工具: 使用Apache Ant和NetBeans IDE构建

robot - 测试用例项目

类型: Robot Framework测试项目

目录结构:

- implementation/testsuites: 测试套件文件
- implementation/resources: 共享资源文件
- execution/local: 本地执行脚本和配置
- output: 测试结果输出目录
