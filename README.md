# Mrigank Bhatnagar

Systems software engineer focused on low-level infrastructure, database storage engines, and high-throughput network runtimes. Specializing in zero-allocation architectures, Linux internals, and deterministic agentic execution.

[![Portfolio](https://img.shields.io/badge/Portfolio-mrigankbhatnagar.dev-1B6B99?style=flat-square&logo=safari&logoColor=white)](https://mrigankbhatnagar.dev)
[![GitHub](https://img.shields.io/badge/GitHub-Awesome06-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/Awesome06)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-mrigank--bhatnagar-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/mrigank-bhatnagar)
[![Email](https://img.shields.io/badge/Email-bhatnagar.mrigank2006@gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:bhatnagar.mrigank2006@gmail.com)
[![LeetCode](https://img.shields.io/badge/LeetCode-Knight%20(Top%201.6%25)-FFA116?style=flat-square&logo=leetcode&logoColor=white)](https://leetcode.com/u/vgF0f3VhNO/)

---

### Core Systems & Flagship Projects

- **[Fracture Benchmarking Suite](https://github.com/switchstonedev/fracture-bench)** (Rust, Linux, cgroups v2)  
  Open-loop vector database benchmarking harness using hardware Timestamp Counter (TSC) polling instead of kernel `nanosleep` to eliminate OS scheduler jitter. Sustains sub-microsecond arrival pacing and exposed true p99.9 tail latency collapses up to 42.8x higher than conventional closed-loop benchmarks.

- **[Argus TradeGuard](https://github.com/Awesome06/argus-tradeguard)** (C++20, Linux, Python, DuckDB)  
  High-frequency electronic pre-trade risk filter. Replaces mutexes with lock-free SeqLocks to eliminate thread contention and swaps floating-point arithmetic for integer fixed-point math to guarantee deterministic nanosecond validation. Evaluates 50,000+ orders/s at sub-microsecond p99 latency with automated cancel-on-disconnect protection.

- **[Forest Storage Engine](https://github.com/Awesome06/Forest_DatabaseEngine)** (Go, TCP/UDP, TLS 1.3)  
  Crash-safe Log-Structured Merge-Tree (LSM-Tree) key-value engine. Swaps mutex-guarded maps for concurrent lock-free SkipLists to eliminate multi-core write contention, and uses raw binary TCP framing over gRPC to achieve 5.85ns decoding latency and zero heap allocations.

- **[Aegis Zero Trust Proxy](https://github.com/Awesome06/aegis-proxy)** (Go, TCP/UDP, TLS 1.3)  
  High-concurrency L3–L7 Zero Trust forward proxy. Uses lock-free Radix Trees over hash tables for deterministic O(k) CIDR prefix routing, inspecting byte-level TLS 1.3 ClientHello Server Name Indication (SNI) and DNS packets without terminating cryptographic sessions.

- **[NexusGraph](https://github.com/Awesome06/nexusgraph)** (TypeScript, Next.js, FalkorDB)  
  Autonomous multi-agent incident triage swarm. Leverages FalkorDB graph traversal over relational SQL JOINs to trace multi-hop microservice dependency blast radius in O(1) time, orchestrating automated diagnostics via Model Context Protocol (MCP).

---

### Open Source & Engineering Milestones

- **Apache Arrow (`apache/arrow`)**: Core C++ contributor. Merged contributions implementing string view equality comparison kernels ([PR #55171](https://github.com/apache/arrow/pull/55171)) and defaulting Parquet V2 data pages ([PR #55453](https://github.com/apache/arrow/pull/55453)), with active reviews on IPC buffer bounds validation ([PR #55671](https://github.com/apache/arrow/pull/55671)).
- **Apache DataFusion (`apache/datafusion` & `datafusion-python`)**: Upstream open-source contributions across core columnar SQL query execution and Python engine bindings.
- **Google FlatBuffers (`google/flatbuffers`)**: Merged contributions to cross-platform serialization compiler infrastructure.
- **ICPC Regionalist**: Qualified for ICPC Asia West Kanpur Regional (AIR 1443 across 4,500+ teams) and 2x University Topper in ICPC Prelims with team *LambdaSoup*.
- **Competitive Programming Pedigree**: INOI Qualifier, LeetCode Knight (Top 1.6%), and 1,500+ algorithmic problems solved across LeetCode, Codeforces, and CodeChef.

---

### Technical Arsenal

| Layer | Technologies & Tools |
| :--- | :--- |
| **Languages** | C++20, Go 1.22+, Rust, Python, SQL, TypeScript, MIPS Assembly |
| **Systems & Networking** | Linux Internals, POSIX, eBPF, TCP/UDP, TLS 1.3, cgroups v2, Docker Sandboxing |
| **Storage & Data Engines** | LSM-Trees, Write-Ahead Logs, FalkorDB, DuckDB, PostgreSQL, Redis, SQLite |
| **Compilers & Tooling** | CMake, GCC/Clang, GDB, Valgrind, Tree-sitter, Git, Linux / WSL2 |

---

### Contribution Activity

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Awesome06/Awesome06/output/github-contribution-grid-snake-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Awesome06/Awesome06/output/github-contribution-grid-snake.svg">
  <img alt="GitHub Contribution Snake" src="https://raw.githubusercontent.com/Awesome06/Awesome06/output/github-contribution-grid-snake.svg" width="100%">
</picture>
