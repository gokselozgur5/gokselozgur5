Building end-to-end physical, spatial autonomy and frontier AI systems across **VR/AR (OpenXR / Meta Quest 3)**, **Tactical Situational Awareness (TAK / CoT)**, **Robotics (ROS 1 Noetic & ROS 2 Jazzy/Humble)**, **Zero-Dependency LLM Engines & Fine-Tuning (Autograd / FlashAttention / Alignment / RAG)**, **Custom PCB & Embedded Hardware**, and **High-Performance Rust / C++**.

```mermaid
flowchart LR
    HW["PCB & Embedded Sensors"] -->|UART / CAN / Spinnaker| ROS["ROS 1 Noetic & ROS 2 Robotics"]
    ROS -->|Telemetry & Visual Sensing| LLM["First-Principles LLM, Fine-Tuning & RAG"]
    LLM -->|DeepStream & TensorRT| CV["Edge ML & Situational Inference"]
    CV -->|CoT XML / UDP Multicast| TAK["TAK Tactical Network"]
    TAK -->|C-ABI FFI / WebXR| XR["VR & AR Passthrough HUD (Quest 3)"]
```

## Flagship Engineering Systems

| Repository | Domain | Architecture & Verification Highlights |
| :--- | :--- | :--- |
| [**`parallax-core`**](https://github.com/gokselozgur5/parallax-core) | **First-Principles LLM & Deep Learning Engine** | Zero-dependency pure NumPy/math LLM framework: Autograd, FlashAttention-2, FlashDecoding, Ring Attention, DeepSeek MLA, PagedAttention, Speculative Decoding, Muon Optimizer, FP8 GEMM, BitNet b1.58, and direct preference alignment (DPO, ORPO, SimPO, IPO). |
| [**`jessy`**](https://github.com/gokselozgur5/jessy) | **Cognitive AI & Semantic Layer Engine (Rust)** | High-performance multi-layer semantic reasoning core in Rust: 15 cognitive layers, 4-stage observer chain, custom intent-based RAG orchestration, and high-throughput async memory pipelines. |
| [**`xrtak`**](https://github.com/gokselozgur5/xrtak) | **VR / AR + TAK (OpenXR)** | 3D Tactical Sand Table, First-Person Passthrough Visor HUD, bidirectional ATAK CoT bridge, and Rust C-ABI OpenXR core, and [Live Quest 3 WebXR](https://gokselozgur5.github.com/xrtak)
| [**`ar-bot-jimmy`**](https://github.com/gokselozgur5/ar-bot-jimmy) | **Robotics + AR + LLM** | 38 cm Full-Body ROS 2 humanoid with 3-pivot analytical IK, STS3215 serial bus protocol, Embodied LLM Puppeteer, and [Live Quest 3 WebXR Omni-HUD](https://gokselozgur5.github.io/ar-bot-jimmy/web/). |
| [**`ros2-corridor-swarm`**](https://github.com/gokselozgur5/ros2-corridor-swarm) | **ROS 2 + TAK + Edge AI** | ROS 2 Jazzy multi-UGV fleet on Jetson Thor with Gazebo simulation, corridor patrol, geofencing, ATAK CoT feed, and LLM mission planner. |
| [**`orbital-mechanic`**](https://github.com/gokselozgur5/orbital-mechanic) | **Autonomous Robotics** | ROS 2 maintenance robot with Nav2 localization, safety-interlocked repair execution, and LLM fault diagnosis. |
| [**`pcb-design-collar-tracker`**](https://github.com/gokselozgur5/pcb-design-collar-tracker) | **Hardware & PCB Design** | Miniature GPS & cellular tracker with KiCad schematics, multi-layer PCB layout, and DFM verification evidence. |
| [**`runpod-comfyui-i2v-pipeline`**](https://github.com/gokselozgur5/runpod-comfyui-i2v-pipeline) | **Cloud GPU & Generative CV** | Auditable GPU cluster orchestration, video synthesis, and automated quality gates. |

## Core Stack & Capabilities

- **LLM Systems, Pretraining & Fine-Tuning:** First-principles Transformer design, LoRA / DoRA / X-LoRA parameter-efficient fine-tuning, Retrieval-Augmented Generation (RAG) vector retrieval pipelines, RLHF / DPO / ORPO / SimPO / IPO preference optimization, Quantization (FP8, INT8, Ternary BitNet b1.58).
- **High-Performance Rust & Systems:** Async Rust (Tokio), C-ABI FFI bindings, zero-copy memory dispatch, custom high-throughput tokenizers, vector search indexing, SIMD/BLAS integration.
- **Spatial Computing (VR / AR):** OpenXR, Meta Quest 3 Passthrough Mixed Reality, WebXR, Three.js, Spatial Anchors, 3D Tactical HUDs.
- **Robotics & Embedded Hardware:** ROS 1 (Noetic), ROS 2 (Jazzy / Humble), `ros1_bridge` migration, URDF/Xacro, Forward & Inverse Kinematics, MoveIt / Nav2, FLIR Spinnaker camera drivers, Serial Bus Actuators (Dynamixel / Feetech), STM32, Jetson Orin / Thor, KiCad PCB/DFM.
- **Tactical & Edge AI:** ATAK / Cursor-on-Target (CoT), Custom Java ATAK Plugins, NVIDIA DeepStream, GStreamer, TensorRT, Embodied LLM Tool/Gesture Planners.
- **Distributed Messaging & Full-Stack:** Rust, C++, Python, Java, TypeScript (React, Node.js, Three.js), RabbitMQ, Redis, Celery, ZeroMQ, WebSockets, Docker.

## Contact & Profiles

- **Enterprise / Work GitHub:** [github.com/Gozgur](https://github.com/Gozgur)
- **LinkedIn:** [linkedin.com/in/goske](https://www.linkedin.com/in/goske)
- **Direct Inquiries & Rapid R&D Prototyping:** `gokselozgur5@gmail.com`
