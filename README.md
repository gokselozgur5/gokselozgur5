# Göksel Özgür — Spatial, Tactical & Embodied AI Systems Architect

Building end-to-end physical and spatial autonomy systems across **VR/AR (OpenXR / Meta Quest 3)**, **Tactical Situational Awareness (TAK / CoT)**, **Robotics (ROS 1 Noetic & ROS 2 Jazzy/Humble)**, **Edge Computer Vision & ML (DeepStream / TensorRT)**, **Custom PCB & Embedded Hardware**, and **Full-Stack Rust / C++**.

```mermaid
flowchart LR
    HW["PCB & Embedded Sensors"] -->|UART / CAN / Spinnaker| ROS["ROS 1 Noetic & ROS 2 Robotics"]
    ROS -->|Zero-Copy Video & Telemetry| CV["Edge ML / DeepStream & LLM"]
    CV -->|CoT XML / UDP Multicast| TAK["TAK Tactical Network"]
    TAK -->|C-ABI FFI / WebXR| XR["VR & AR Passthrough HUD (Quest 3)"]
```

## Flagship Engineering Systems

| Repository | Domain | Architecture & Verification Highlights |
| :--- | :--- | :--- |
| [**`xrtak`**](https://github.com/gokselozgur5/xrtak) | **VR / AR + TAK (OpenXR)** | 3D Tactical Sand Table, First-Person Passthrough Visor HUD, bidirectional ATAK CoT bridge, and Rust C-ABI OpenXR core. |
| [**`ar-bot-jimmy`**](https://github.com/gokselozgur5/ar-bot-jimmy) | **Robotics + AR + LLM** | 38 cm Full-Body ROS 2 humanoid with 3-pivot analytical IK, STS3215 serial bus protocol, Embodied LLM Puppeteer, and [Live Quest 3 WebXR Omni-HUD](https://gokselozgur5.github.io/ar-bot-jimmy/web/). |
| [**`ros2-corridor-swarm`**](https://github.com/gokselozgur5/ros2-corridor-swarm) | **ROS 2 + TAK + Edge AI** | ROS 2 Jazzy multi-UGV fleet on Jetson Thor with Gazebo simulation, corridor patrol, geofencing, ATAK CoT feed, and LLM mission planner. |
| [**`orbital-mechanic`**](https://github.com/gokselozgur5/orbital-mechanic) | **Autonomous Robotics** | ROS 2 maintenance robot with Nav2 localization, safety-interlocked repair execution, and LLM fault diagnosis. |
| [**`pcb-design-collar-tracker`**](https://github.com/gokselozgur5/pcb-design-collar-tracker) | **Hardware & PCB Design** | Miniature GPS & cellular tracker with KiCad schematics, multi-layer PCB layout, and DFM verification evidence. |
| [**`runpod-comfyui-i2v-pipeline`**](https://github.com/gokselozgur5/runpod-comfyui-i2v-pipeline) | **Cloud GPU & Generative CV** | Auditable GPU cluster orchestration, video synthesis, and automated quality gates. |

## Core Stack & Capabilities

- **Spatial Computing (VR / AR):** OpenXR, Meta Quest 3 Passthrough Mixed Reality, WebXR, Three.js, Spatial Anchors, 3D Tactical HUDs.
- **Robotics & Embedded Hardware:** ROS 1 (Noetic), ROS 2 (Jazzy / Humble), `ros1_bridge` migration, URDF/Xacro, Forward & Inverse Kinematics, MoveIt / Nav2, FLIR Spinnaker camera drivers, Serial Bus Actuators (Dynamixel / Feetech), STM32, Jetson Orin / Thor, KiCad PCB/DFM.
- **Tactical & Edge AI:** ATAK / Cursor-on-Target (CoT), Custom Java ATAK Plugins, NVIDIA DeepStream, GStreamer, TensorRT, Embodied LLM Tool/Gesture Planners.
- **Distributed Messaging & Full-Stack:** Rust, C++, Python, Java, JavaScript / TypeScript (React, Node.js, Three.js), RabbitMQ, Redis, Celery, ZeroMQ, WebSockets, Docker.

## Contact & Profiles

- **Enterprise / Work GitHub:** [github.com/Gozgur](https://github.com/Gozgur)
- **LinkedIn:** [linkedin.com/in/goske](https://www.linkedin.com/in/goske)
- **Direct Inquiries & Rapid R&D Prototyping:** `gokselozgur5@gmail.com`
