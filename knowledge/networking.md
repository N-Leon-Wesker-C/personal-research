# Networking

> 返回 [知识索引](../KNOWLEDGE.md)

## 概览

从协议栈到数据中心网络；关注高吞吐、低延迟的数据面与网络可编程性。

## 概念地图

- **协议**：TCP、QUIC、HTTP/2/3、拥塞控制（CUBIC / BBR）
- **高性能数据面**：DPDK、io_uring、AF_XDP、RDMA（RoCEv2）
- **可编程**：eBPF / XDP、P4
- **数据中心**：叶脊拓扑、ECN、负载均衡、多路径
- **观测**：tcpdump / Wireshark、perf、eBPF 工具链

## 关键问题

- 100G+ 环境下，内核协议栈的瓶颈在哪里？
- RDMA 的部署门槛与可靠性问题如何权衡？
- 拥塞控制如何与上层应用（如推理 KV 传输）协同？
- 网络可编程性的收益是否值得运维复杂度？

## 笔记

<!-- 格式：
### 2026-10-28 · 标题

- 来源：
- 要点：
- 疑问：
-->

## 资源

- Computer Networking: A Top-Down Approach
- RFC 9000（QUIC）
- NSDI / SIGCOMM 论文
