
一、基本情况
四种主要监控方式
1:Logging discrete event file 监控告警
2:Tracing cat调用链chain,request scoped 监控告警
3:Metrics aggregatable (db label) 监控告警
4:HealthChecks 

prometheus包含metrics healthChecks

二、BusDevOps和测量驱动开发MDD
1:DevOps开发运维一体化
(1)System flow from left to right 系统思维 迁移
(2)Amplify feed-back loops 强化反馈环
(3)Culture of Continental experimentation and learning

CALMS模型
•Culture
•Automation 自动化
•Lean IT
•Measurement 测量(metrics)
•Sharing

DevOps理念：要提升必先测量
DevOps实践：研发自助监控
You build it, you run it, you monitor it.

精益创业反馈环
问题
(1)运维人员只专注系统监控(日志，负载度量)，没有应用监控能力和上下文
(2)开发人员只管实现功能，没有DevOps和度量意识
(3)应用监控空白，对应用状态无感知，主要靠蒙
(4)业务对关键应用指标无感知，很多功能开发了也无人用

Test Driven Development(TDD)
Metrics Driven Development(MDD)

MDD核心原理
开发功能前先定义度量指标(Bus/Dev/Ops)
•Define metrics before development
开发人员自助埋点
•Instrumentation-as-Code
真实性的唯一来源
•Single Source of Truth
关键指标的共同视角
•Shared view of key metrics
使用度量进行决策
•Use metrics when making decisions
开发持续维护指标
•Maintain and follow metrics



