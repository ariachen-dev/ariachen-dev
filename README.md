# Aria Chen

Distributed systems engineer based in Taipei.  
Focusing on asynchronous worker pools, task scheduling, serialization protocols, and pipeline latency reduction.

---

### 📡 Open Source Work & Contributions

* **[celery/celery](https://github.com/celery/celery)** — Worker execution state machines, revoked stamped headers, and timer reconciliation.
* **[ijl/orjson](https://github.com/ijl/orjson)** — Serialization benchmarks and buffer allocation in high-throughput pipelines.
* **[msgpack/msgpack-python](https://github.com/msgpack/msgpack-python)** — Binary protocol unpacking and stream boundary validation.

---

### ⚙️ Systems Philosophy

- **Zero-Drop Invariants**: Distributed workers must never drop task timers or time limits across broker reconnections.
- **Minimal Atomic Commits**: Keep pull requests surgical, fully tested, and cleanly rebased.
- **Comprehensive Benchmarks**: Measuring throughput and memory allocation across high-load scenarios.

---
*Distributed Systems • Asynchronous Queues • Low-Latency Serialization • Python*
