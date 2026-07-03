# 🚀 Nova Drive (Core Engine)

Nova Drive is a high-performance, next-generation cloud storage ecosystem designed to challenge resource-heavy alternatives. By utilizing a **5-layer native system architecture**, Nova Drive focuses on extreme memory efficiency, absolute privacy via local cryptographic enforcement, and ultra-fast local network routing.

---

## 🛠️ System Architecture Blueprint

Nova Drive splits its workload across distinct technical layers to achieve bare-metal performance while maintaining a clean, modern user experience:

*   **Core Database & Orchestration (Rust):** Manages asynchronous SQLite metadata operations, handles internal API authentication, and coordinates low-level object management with a minimal binary footprint.
*   **Cryptographic Heavy-Lifter (C++):** Drives the secure local vault system. Encrypts and chunks files on the client side using optimized binary stream manipulations before they ever touch the network.
*   **Bare-Metal Networking (C):** Manages the **P2P LAN Sync** infrastructure using low-level socket programming (TCP/UDP) to stream massive files directly between local network devices at hardware limits without using internet bandwidth.
*   **Edge Intelligence (Python):** Runs an isolated asynchronous indexing script in the background to parse and build text indexes from documents for secure local semantic search capabilities.
*   **API Gateway & Router (Node.js):** Acts as the primary entry point, hosting the lightweight local server and coordinating real-time UI updates via WebSockets.
*   **User Interface (HTML, CSS, Vanilla JS):** A clean, highly responsive **Cyber-Dark** dashboard designed for tech enthusiasts, developers, and speed-focused users.

---

## 👥 Open Core Contributor Positions

We are looking for dedicated core developers who love low-level engineering and optimization to join the foundational team. 

### 1. C Core Networking Engineer
*   **Focus:** Implement reliable local P2P file transfer protocols using raw BSD sockets.
*   **Tech Stack:** C murni, POSIX Threads, TCP/UDP Socket Programming.

### 2. C++ Cryptography Specialist
*   **Focus:** Architect high-throughput binary file streaming, chunking, and localized secure encryption routines.
*   **Tech Stack:** Modern C++, Bitwise Operations, File Streams (`std::ifstream`).

### 3. Python AI & Indexing Engineer
*   **Focus:** Build lightning-fast document parsers and keyword text extractors that run silently with zero CPU spikes.
*   **Tech Stack:** Python, Regex, `sqlite3`, File I/O.

### 4. Node.js & JS Integration Master
*   **Focus:** Maintain the local routing gateway and bind backend binaries to the responsive vanilla frontend via the Streams API.
*   **Tech Stack:** Node.js, Express, JavaScript (Fetch API, DOM, WebSockets).

---

## 📅 Roadmap & Milestones

1.  **Phase 1 (Core Foundation):** Finalize the Rust core database, optimize local C++ cryptography routines, and deploy the responsive Cyber-Dark UI.
2.  **Phase 2 (LAN Acceleration):** Deploy the C-based P2P LAN Sync system for zero-bandwidth high-speed transfers.
3.  **Phase 3 (Sovereign Cloud):** Introduce highly scalable, decentralized backend scaling while keeping user data private and secure.

---
*Built with passion by Nova Labs. Let's make cloud storage fast and sovereign again.*
