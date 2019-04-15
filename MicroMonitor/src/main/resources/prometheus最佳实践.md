四个黄金指标(Google)
延迟：服务请求所需耗时
•例如HTTP请求平均延迟
流量/吞吐：衡量服务容量需求
•例如每秒处理HTTP请求数
错误：衡量错误发生的情况
•例如HTTP 500错误数
饱和度：衡量资源使用情况
•例如CPU/内存/磁盘使用量

三类系统的监控
Online Serving System
• RED方法
• Requests
• Errors
• Duration
• Cache
• 命中率

Offline Serving System
• USE方法
• Utilization
• Saturation
• Errors
• 线程池类似

Batch Jobs
• Pushgateway
• 指标
• Job运行时长
• 每阶段时长
• 失败/成功数

Cardinality(基数)
**• Label的可能取值**
**• 新增一个Label值=新增一个时间序列**
**• 经验值：单实例Cardinality <= 10个**
**• 不适合做Label**
• Email地址
• 用户名
• IP地址
• HTTP Path
**• 关注10个最大的metrics**
**• 高Cardinality场景用Log系统**
8020原则


四层轻量监控体系
