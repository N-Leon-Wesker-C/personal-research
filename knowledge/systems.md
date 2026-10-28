# Systems

> 返回 [知识索引](../KNOWLEDGE.md)

## 概览

操作系统、分布式系统、存储与虚拟化的交叉地带；关注真实系统中的性能、正确性与可运维性。

## 概念地图

- **OS**：调度、虚拟内存、文件系统、io_uring、eBPF
- **虚拟化**：KVM、Firecracker、容器与命名空间、cgroup
- **分布式**：一致性模型、共识（Raft）、复制、故障模型
- **存储**：LSM-tree、WAL、缓存层级、对象存储
- **性能**：吞吐 / 延迟、尾延迟、排队论、perf / flamegraph

## 关键问题

- 端到端尾延迟由哪一层主导？如何系统性地定位？
- 内核旁路 vs 内核内处理（eBPF / io_uring）如何取舍？
- 分布式系统的「简单可运维」如何量化与验证？
- 资源隔离（CPU / 内存 / IO）在混部场景下是否可靠？

## 笔记

<!-- 格式：
### 2026-10-28 · 标题

- 来源：
- 要点：
- 疑问：
-->

## 资源

- OSTEP（Operating Systems: Three Easy Pieces）
- Designing Data-Intensive Applications
- OSDI / SOSP / USENIX ATC / FAST 论文
