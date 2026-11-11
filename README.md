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
| [**`pcb-design-collar-tracker`**](https://github.com/gokselozgur5/pcb-design-collar-tracker) | **Hardware & PCB Systems** | Miniature GNSS and cellular tracking platform: KiCad multi-layer schematics, impedance-controlled RF routing, nano-SIM layout, and DFM verification. |

## Core Technical Stack

- **Systems & Embedded:** Rust (`#![no_std]`, embedded-hal), C/C++, STM32 Cortex-M4F, RTOS, memory-mapped I/O, UART, CAN 2.0B, SPI, I2C, COBS, CRC codecs.
- **Perception & State Estimation:** Extended Kalman Filtering (Joseph stabilized, NIS gating), SO(3) strapdown kinematics, monocular 3D ranging, WGS84/ECEF geodesy, multi-target tracking.
- **Spatial Computing & Tactical Networking:** WebXR, OpenXR, Three.js, Cursor-on-Target (CoT 2.0 XML over UDP multicast), ATAK plugin architecture, C-ABI FFI bindings.
- **Autonomous Robotics & Hardware Design:** ROS 2 (Jazzy/Humble), analytical inverse kinematics, serial actuator buses, KiCad schematic and PCB design, DFM layout verification.
