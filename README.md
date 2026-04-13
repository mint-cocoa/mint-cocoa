## Jinhu Bae

Game server developer building high-performance real-time systems in C++ on Linux.

Focused on async I/O architecture, network protocol design, and system-level optimization for game servers that handle thousands of concurrent connections.

---

### Projects

**[libiouring-server](https://github.com/mint-cocoa/libiouring-server)** — io_uring-based C++ Game Server Framework

Production-grade async I/O server using Linux io_uring instead of epoll. Multishot Accept/Recv with provided buffers for zero-copy I/O, MSG_RING cross-ring communication, and a 4-phase symmetric event loop. Benchmarked at 327K echo/s throughput and 3.1M msg/s in separated architecture.

`C++20` `io_uring` `Linux` `Protobuf`

---

**[game-client](https://github.com/mint-cocoa/game-client)** — DirectX 11 Isometric Multiplayer Client

Full-featured multiplayer dungeon RPG client (~6,200 LOC) built directly on the DX11 API without any game engine. StructuredBuffer instancing reduced draw calls from 4,640 to 8. 59-message binary protocol over Protobuf with deterministic procedural dungeon generation.

`C++` `DirectX 11` `Protobuf` `WinSock2`

---

**[portfolio](https://github.com/mint-cocoa/portfolio)** — Technical Portfolio

Detailed write-ups covering architecture decisions, benchmark results, and problem-solving process for each project above.

---

### Tech Stack

| Category | |
|---|---|
| **Languages** | C++20, C, Python |
| **System** | io_uring, epoll, Linux kernel I/O |
| **Graphics** | DirectX 11, HLSL |
| **Network** | Protobuf, WinSock2, TCP |
| **Infra** | Docker, Kubernetes, GitHub Actions |

