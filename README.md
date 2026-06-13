# Edgar Muñoz

**Senior Software Engineer | GPU Kernel Optimization & AI Inference** Mexico (TN Visa Eligible)
[LinkedIn](https://www.linkedin.com/in/edgarmuvaz) · [Email](mailto:edgarmuvaz@gmail.com)

---

### Profile

Senior Software Engineer with over 7 years of experience building, scaling, and observing high-availability distributed systems at industry-leading companies, including Apple and Microsoft[cite: 18, 27]. Expertise spans processing terabyte-scale datasets using Apache Spark, managing robust gRPC APIs, and architecting cloud-native microservices on Kubernetes and Azure[cite: 22, 23, 30, 43]. 

Currently channeling this deep architectural knowledge into low-level hardware optimization, focusing on GPU kernel engineering, memory management, and accelerating AI inference pipelines. My goal is to bridge the gap between heavy distributed cloud infrastructure and bare-metal performance, driving maximum throughput and minimal latency by writing optimized execution paths directly for the silicon.

---

### Core Expertise

* **GPU Architecture & Kernels:** Writing and optimizing custom CUDA kernels, thread/block layout design, capitalizing on compute intensity.
* **Memory Hierarchy Tuning:** Maximizing bandwidth through memory coalescing, shared memory tiling, and strict mitigation of shared memory bank conflicts.
* **Low-Level Primitives:** Implementing high-performance parallel reductions and scans using warp-level primitives (`__shfl_sync`).
* **Mixed-Precision Computing:** Utilizing Tensor Cores via WMMA/MMA instructions for quantized (INT8/FP16) compute pipelines.
* **Production Deployment:** Packaging high-performance kernels into PyTorch C++ Extensions and architecting production-grade, low-latency inference pipelines with Triton Inference Server.

---

### Technical Stack

```text
Hardware / AI :: CUDA, C++, PyTorch, Triton Inference Server, PTX
Systems Arch  :: Kubernetes, Kafka, gRPC, Apache Airflow, Docker
Languages     :: C++, CUDA, Python, Java, C#
