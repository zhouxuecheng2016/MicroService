
https://www.ibm.com/developerworks/cn/cloud/library/cl-lo-prometheus-getting-started-and-practice/index.html

什么是Prometheus
•开源监控工具
•时间序列数据库TSDB，golang实现
•Soundcloud研发，源于谷歌borgmon
•多维度(标签)，拉模式(Pull-based)
•白盒&黑盒监控都支持，DevOps友好
•Metrics & Alert，不是
  loggging/tracing
•社区生态丰富(多语言，各种exporters)
•单机性能
  消费百万级时间序列
  上千个targets

Prometheus架构设计

Prometheus基本概念
Metrics种类
• Counter(计数器)
   始终增加
   http请求数，下单数
• Gauge(测量仪)
   当前值的一次快照(snapshot)测量，可增可减
   磁盘使用率，当前同时在线用户数
• Histogram(直方图)
   通过分桶(bucket)方式统计样本分布
• Summary(汇总)
   根据样本统计出百分位
   客户端计算







