# AI Infra

> 返回 [知识索引](../KNOWLEDGE.md)

## 概览

支撑大模型训练与推理的系统层：算力、内存、通信、调度与服务的协同设计。

## 概念地图

- **训练**：数据 / 张量 / 流水线并行、ZeRO、混合精度、checkpoint
- **推理**：prefill / decode、continuous batching、投机解码
- **KV cache**：PagedAttention、前缀缓存、分层与解耦、传输
- **硬件**：GPU / NPU、HBM、NVLink、RDMA、互联拓扑
- **服务**：vLLM、SGLang、Triton、调度与 SLA
- **指标**：吞吐、TTFT、TPOT、GPU 利用率、显存碎片

## 关键问题

- 推理瓶颈在算力、显存带宽，还是 KV cache 的容量 / 传输？
- 解耦式（disaggregated）架构在什么负载下真正划算？
- 调度如何同时优化吞吐与尾延迟？
- 前缀缓存 / 多轮对话场景下，cache 复用与一致性的边界？

## 笔记

<!-- 格式：
### 2026-10-28 · 标题

- 来源：
- 要点：
- 疑问：
-->

## 资源

- vLLM / SGLang 文档与论文
- DistServe、Splitwise、Mooncake（待读，读后补充结论）
- MLSys / OSDI / NSDI 相关论文

## 关联项目

- [Disaggregated KV Cache](../projects/disaggregated-kvcache.md)
