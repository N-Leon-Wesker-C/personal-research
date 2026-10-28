# Rust Systems

> 返回 [知识索引](../KNOWLEDGE.md)

## 概览

Rust 在系统软件中的定位：内存安全 + 无 GC + 接近 C/C++ 的性能，代价是所有权的编译期约束和更陡的学习曲线。

## 概念地图

- **所有权 / 借用 / 生命周期**：移动语义、`&` / `&mut`、NLL
- **抽象**：trait、泛型单态化、零成本抽象、`dyn` 动态分发
- **异步**：`async`/`await`、`Future`、`Pin`、执行器（tokio）
- **底层**：`unsafe`、裸指针、FFI、`repr(C)`、内存布局
- **并发**：`Send`/`Sync`、`Arc`/`Mutex`、`crossbeam`、无锁结构
- **常用 crate**：`bytes`、`tokio`、`hyper`、`serde`、`rayon`
- **系统案例**：Rust for Linux、Firecracker、用户态网络 / 存储数据面

## 关键问题

- 什么时候必须 `unsafe`？如何把不安全代码隔离在最小边界内？
- async 的取消安全（cancellation safety）如何影响协议与状态机实现？
- Rust 在零拷贝、io_uring、RDMA 场景中的表现与坑？
- 编译时间、二进制体积、生态成熟度在系统项目中的实际代价？

## 笔记

<!-- 格式：
### 2026-10-28 · 标题

- 来源：
- 要点：
- 疑问：
-->

## 资源

- The Rust Programming Language（官方书）
- Rustonomicon（unsafe 与底层细节）
- tokio / async book
