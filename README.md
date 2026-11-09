# DBMS Engineering Group
 
**A community of engineers and researchers building, studying and benchmarking database systems from the storage layer up.**
 
[Website](https://dbms.engineering) · [Join](https://dbms.engineering) · [Discord](DISCORD_INVITE_URL) · [Comnet Laboratory](https://comnet.oauife.edu.ng/)
 
---
 
## Who we are
 
DBMS Engineering Group is an open community for people who care about how databases actually work: storage engines, query execution, concurrency control, and the kernel and hardware underneath them. We read papers together, build experimental systems, and measure everything.
 
We're interested in questions like:
 
- How do kernel I/O primitives (`epoll`, `io_uring`, direct I/O) shape storage engine performance?
- Where does latency really come from, across the runtime, the OS and the CPU?
- What changes when the database and the application runtime are designed together?
## What we work on
 
| Area | Focus |
| --- | --- |
| **Storage engines** | Page layout, buffer management, log-structured vs. B-tree designs |
| **Asynchronous I/O** | `io_uring`, `epoll` and their effect on throughput, tail latency and syscall overhead |
| **Runtime / database co-design** | Experimental work inspired by *Serverless Runtime / Database Co-Design With Asynchronous I/O* (Enberg et al., EdgeSys '24) |
| **Benchmarking methodology** | Reproducible, statistically sound performance testing |
