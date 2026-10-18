# Aria Chen // Taipei

Distributed systems engineer.  
Focusing on asynchronous worker pools, task scheduling, serialization protocols, and pipeline latency reduction.

---

### 📡 Active Upstream Ledger

* **[celery/celery](https://github.com/celery/celery)** — Worker execution state machines, revoked stamped headers, and timer reconciliation.
* **[ijl/orjson](https://github.com/ijl/orjson)** — Serialization benchmarks and buffer allocation in high-throughput pipelines.
* **[msgpack/msgpack-python](https://github.com/msgpack/msgpack-python)** — Binary protocol unpacking and stream boundary validation.

---

### ⚙️ Systems Philosophy

- **Zero-Drop Invariants**: Distributed workers must never drop task timers or time limits across broker reconnections.
- **Minimal Atomic Commits**: Keep pull requests surgical, fully tested, and cleanly rebased.
- **Pre-Flight CI Airlock**: Diff minimization and regression checking executed via [ZeroSlop™ CI](https://github.com/marketplace/actions/zeroslop-by-ribbsaeter-systems).

---
*Distributed Systems • Asynchronous Queues • Low-Latency Serialization*
