# 会议纪要 -- 中文
# 2023.01.12
## 参会人
蔡铭霞（阿里云）
杨传坤(移动)
张斌斌（滴滴）
龚华健（西安电子科技大学）

## 主要主题
分享下23年的规划，并根据制定的roadmap进行工作细分
[2023-roadmap](doc/23年开源roadmap.pptx)

## 讨论
* redis压测流量识别不到，可以通过key来做匹配

# 2023.02.09
## 参会人
蔡铭霞（阿里云）
杨传坤(移动)
张斌斌（滴滴）
龚华健（西安电子科技大学）
...

## 主要主题
主要有如下几块进展讨论
1. 官网增加工具文档
2. 23年roadmap 拆分为不同issue
3. issue讨论

## 讨论
* ebpf具体要支持哪些功能

# 2023.02.23
## 主讲人
蔡铭霞（阿里云）
曹付江(移动)
李森森(移动)
...

## 主要主题
主要同步目前社区正在进行的几个项目：
1. 增加内核场景ebpf的支持
2. 增加对server端redis的支持
3. 增加对http的支持
4. 增加对network的支持

## 讨论
* 限制redis的maxmemory主要是想让产品团队做什么方面的优化呢？
maxmemory的作用，是当Redis 执行写操作时，发现内存超出 maxmemory，就会执行一次LRU淘汰算法。通过尝试设置不同大小的maxmemory的，触发LRU淘汰算法的场景

# 2023.03.09
## 主讲人
蔡铭霞（阿里云）
曹付江(移动)
李森森(移动)
...

## 主要主题
主要同步目前社区正在进行的几个项目的进展：
1. 增加内核场景ebpf的支持
2. 增加对server端redis的支持
3. 增加对http的支持
4. 增加对network的支持

# 2023.04.06
## 主讲人
蔡铭霞（阿里云）
...
## 主要主题
chaosblade内核演练实现 方案介绍
