# Research

> 研究问题与 idea 索引。项目是「在做的」，这里是「在想和想做的」。

## 研究问题

| # | 问题 | 状态 | 关联 | 下一步 |
| --- | --- | --- | --- | --- |
| Q1 | KV cache 解耦 / 分层后，调度与传输的瓶颈在哪里？ | 开放 | [ai-infra](knowledge/ai-infra.md), [networking](knowledge/networking.md) | 梳理 DistServe / Splitwise / Mooncake |
| Q2 | Rust 在用户态网络 / 存储数据面中的边界在哪里？ | 开放 | [rust-systems](knowledge/rust-systems.md), [systems](knowledge/systems.md) | 收集 io_uring / RDMA 的 Rust 实践 |
| Q3 | 异构内存层级如何改变推理服务的容量-延迟权衡？ | 开放 | [systems](knowledge/systems.md) | 建立成本模型 |

## Idea 池

| Idea | 一句话 | 状态 | 笔记 |
| --- | --- | --- | --- |
| — | — | — | — |

## 状态说明

- **开放**：还没投入，只记录问题。
- **探索中**：在查资料 / 做小实验，笔记在 [research/ideas/](research/ideas/)。
- **已立项**：有自己的项目页，在 [projects/](projects/)。
- **搁置 / 放弃**：保留结论，避免重复踩坑。

## 立项标准

一个 idea 进入 `projects/` 前，至少能回答：

1. 要解决的具体问题是什么？
2. 现有方案为什么不够？
3. 最小可验证实验是什么？
