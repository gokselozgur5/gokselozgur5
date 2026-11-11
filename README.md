# Göksel Özgür

Systems and autonomous robotics engineer building deterministic navigation cores, spatial perception pipelines, and embedded edge systems. Focused on `#![no_std]` Rust architectures, real-time monocular 3D tracking, tactical CoT telemetry, and production hardware integration.

## Selected Engineering Systems

| Repository | Domain | Core Architecture & Verification Highlights |
| :--- | :--- | :--- |
| [**`stm32-navcore`**](https://github.com/gokselozgur5/stm32-navcore) | **Deterministic Embedded Navigation** | `#![no_std]` zero-alloc Rust navigation engine for STM32 Cortex-M4F with strapdown SO(3) attitude, Joseph-form IMU/GNSS EKF, and COBS/CRC-16/CAN telemetry. |
| [**`sightline-cot`**](https://github.com/gokselozgur5/sightline-cot) | **Real-Time Spatial Vision & CoT** | Pure Rust monocular 3D ranging, fisheye back-projection, Joseph-stabilized Kalman tracking, WGS84 geodesy, and zero-alloc CoT 2.0 XML UDP broadcast with C-ABI. |
| [**`parallax-core`**](https://github.com/gokselozgur5/parallax-core) | **First-Principles Deep Learning Core** | Zero-dependency mathematical LLM engine: Autograd, FlashAttention-2, FlashDecoding, Ring Attention, DeepSeek MLA, PagedAttention, FP8 GEMM, and alignment primitives. |
| [**`xrtak`**](https://github.com/gokselozgur5/xrtak) | **Spatial Computing & Tactical Mixed Reality** | 3D Geospatial Sand Table, First-Person Passthrough Visor HUD, bidirectional ATAK CoT telemetry bridge, and Rust C-ABI OpenXR core on Meta Quest 3. |
| [**`ar-bot-jimmy`**](https://github.com/gokselozgur5/ar-bot-jimmy) | **Robotics Kinematics & Companion Agent** | Modular ROS 2 humanoid companion robot with 3-pivot analytical inverse kinematics, serial bus servo control, embodied agent puppeteer, and WebXR hologram link. |
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
