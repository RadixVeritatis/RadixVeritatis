## RadixVeritatis | Edge AI Engineer | Embedded Systems & MLOps | ECSE (Honours)

Systems engineer focused on **Physical AI**—developing high-reliability, closed-loop systems integrating edge perception, deterministic decision-making, and physical actuation. Specialized in optimizing resource-constrained ARM64 compute environments, eliminating runtime overhead, and hardening deployment infrastructure.

### 🛡️ Core Competencies
* **Perception & Compute:** Computer Vision (OCR/Detection), DSP/Digital Filtering, Vector Space Normalization, Multi-Model Orchestration.
* **Edge Optimization:** ONNX Runtime Optimization (Intra-Op Thread Tuning), INT8 Dynamic Quantization, Linux CFS Context-Switch Mitigation.
* **Infrastructure & MLOps:** Docker (Shared Memory/IPC Tensor Tuning), PostgreSQL (pgvector/HNSW), Stateless Inference Engines, CI/CD Gate Automation.

### 🔬 Featured Project Archetype

#### **[AskVigil: Real-Time Multimodal Security Engine](https://github.com/RadixVeritatis/AskVigil)**
* **Deterministic Latency:** Engineered a Retrieval-Augmented Classification (RAC) pipeline executing model inference and Explainable AI (XAI) feature attribution in **0.095s to 0.181s** on bare-metal ARM64 loops.
* **Hardware-Level Governance:** Isolated high-intensity inference models from state persistence layers using hard Docker resource constraints, mathematically capping PostgreSQL I/O via `blkio_config` (400 IOPS limits) to guarantee zero DB corruption under full compute load.
* **Cache Saturation:** Designed a "Triple-Fire" engine warmup routine that saturates CPU L2/L3 caches on container instantiation, neutralizing 5-second cold-start penalties for real-time edge availability.

---
*Targeting technical roles within Industrial Automation, Autonomous Logistics (AMRs), Critical Infrastructure, and Medical Technology.*
