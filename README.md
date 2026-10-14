# 🌐 Distributed Systems Projects

Projects for the Distributed Systems course (Computer Engineering, University of Tehran), from low-level IPC in Go to a research project on semantic routing in Named Data Networking.

<p>
  <img src="https://img.shields.io/badge/Go-00ADD8?style=flat&logo=go&logoColor=white">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white">
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white">
  <img src="https://img.shields.io/badge/ndnSIM-555555?style=flat">
</p>

| Project | Summary |
|---|---|
| [CA1](CA1) | Go fundamentals: a client–worker calculator over named pipes with a JSON protocol, a benchmark of the Go scheduler on CPU-bound vs. mixed workloads, and a containerised HTTP microservice with middleware |
| [CA2](CA2) | Multi-VM system: authentication server, file server and web dashboard communicating via RPC, plus a publish/subscribe service |
| [CA3](CA3) | Replicated key-value store with three replicas — eventual vs. strong (majority-quorum) consistency, with latency and convergence experiments |
| [Final Project](Final_Project) | **Gossip-scaled semantic forwarding in NDN** — routers share semantic name resolutions through epidemic gossip and audit peers with a reputation mechanism; Python discrete-event simulator cross-checked against ndnSIM |

Each project folder has its own README and report.
