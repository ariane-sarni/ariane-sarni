# Ariane M. Sarni
**Software Engineer (Systems & Robotics)**
San Jose, CA

Systems engineer focused on C++ performance, embedded firmware, and autonomous vehicle infrastructure. Previously at **LKC Technologies**, 
**Skyline Nav AI** and **UCSC**.

### Technologies
* **Languages:** C++, Python, C, CUDA, Bash
* **Systems:** Linux (Arch/Kernel), RTOS, Docker, CMake
* **Robotics:** ROS2, Gazebo, CARLA, MAVLink, PyTorch

---

### Active Projects

**[`zero-copy-ring-buffer`](https://github.com/ariane-sarni/zero-copy-ring-buffer)**
Zero-copy Inter-Process Communication (IPC) library using Linux Shared Memory.
* Implements a lock-free ring buffer to pass high-bandwidth data between processes without kernel-space copying.
* *Focus:* Lock-free concurrency (C++20 atomics), Low-latency architecture.

**[`cuda-fast-tracker`](https://github.com/ariane-sarni/cuda-fast-tracker)**
Real-time computer vision feature tracker written in raw CUDA.
* Custom kernel implementation benchmarking 60+ FPS on 4K video streams by bypassing standard library overhead.
* *Focus:* GPU acceleration, SIMD, Parallel memory access.

**[`cpp-lockfree-arena`](https://github.com/ariane-sarni/cpp-lockfree-arena)**
Deterministic memory allocator for real-time embedded systems.
* Enforces O(1) allocation and contiguous memory layout to eliminate heap fragmentation and jitter in control loops.
* *Focus:* Memory safety, Cache locality, Embedded constraints.

---

### Patents
* **Multi-modal localization** (US App 19/073,770) – Filed Mar. 2025

---
[LinkedIn](https://www.linkedin.com/in/ariane-sarni) | [Email](mailto:arianesarni@gmail.com)
