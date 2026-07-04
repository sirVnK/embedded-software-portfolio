# Embedded Software Engineering Portfolio

Embedded and edge systems built around reliable device software, networking, sensors, industrial protocols, and hardware-aware integration.

## About

Embedded Software Engineering is where my electrical and electronics background meets software. I am developing this track through C++ and Rust systems, Raspberry Pi and ESP32 platforms, embedded Linux, device onboarding, sensor telemetry, and industrial communication. The goal is to show tested behavior on constrained or hardware-connected systems, not only application-layer prototypes.

## Focus Areas

- Modern C++ and Rust for device and edge software
- Raspberry Pi, ESP32, STM32, and embedded Linux
- Wi-Fi provisioning, local networking, and IoT gateways
- Sensor acquisition, telemetry, buffering, and fault handling
- CAN, Modbus RTU/TCP, and serial communication
- PLC integration and industrial automation fundamentals
- Cross-compilation, CMake, testing, logging, and CI
- Edge AI integration, RTSP cameras, and hardware accelerators

## Projects

| Project | Scope | Evidence to publish | Status |
| --- | --- | --- | --- |
| [edge-wifi-provisioning-showcase](https://github.com/sirVnK/edge-wifi-provisioning-showcase) | Public architecture and demo for headless Wi-Fi provisioning and rollback | Screenshot/video, state-transition test matrix | **Completed** |
| [edge-wifi-provisioning-core](https://github.com/sirVnK/edge-wifi-provisioning-core) | Rust implementation for scan, hotspot fallback, setup API, DHCP wait, and rollback | Keep private; publish only sanitized evidence | **In Progress · Private** |
| [skyvision-control-case-study](https://github.com/sirVnK/skyvision-control-case-study) | Sanitized ESP32 sensor, telemetry, Flutter, RTSP, and AI system case study | Interface contracts, synthetic telemetry demo | **In Progress** |
| [hailoai](https://github.com/sirVnK/hailoai) | Raspberry Pi 5 and Hailo NPU runtime benchmark | Hardware setup, thermal/latency results, recovery notes | **In Progress** |
| [gps_tracker](https://github.com/sirVnK/gps_tracker) | Flutter map UI driven by simulated GPS telemetry | Demo GIF and explicit simulated-data label | **Completed Demo** |
| [PLC-Basics-Summary](https://github.com/sirVnK/PLC-Basics-Summary) | PLC fundamentals study notes | Add original exercises and simulation screenshots | **Learning** |
| `stm32-sensor-node` | Planned STM32 firmware for sampled sensor data and fault-aware telemetry | Schematic, firmware, tests, measured timing | **Planned** |
| `can-bus-diagnostics-tool` | Planned C++/SocketCAN diagnostics and log parser | Virtual CAN tests, DBC example, CLI documentation | **Planned** |
| `modbus-iot-gateway` | Planned Rust gateway between Modbus RTU/TCP and MQTT | Simulator, reconnect behavior, integration tests | **Planned** |
| `esp32-industrial-telemetry-node` | Planned ESP32 sensor node with local buffering and watchdog handling | Synthetic sensor demo, power/recovery notes | **Planned** |

## Roadmap

### 3 Months

- Publish a reproducible demo and state-machine test matrix for Wi-Fi provisioning.
- Add synthetic telemetry and interface contracts to the SkyVision case study.
- Build the first STM32 sensor-node milestone with documented timing and serial output.
- Separate embedded evidence from UI-only demos in project descriptions.

### 6 Months

- Complete CAN diagnostics and Modbus gateway projects using simulators before hardware tests.
- Add hardware-in-the-loop or bench-test evidence to at least two repositories.
- Standardize CMake/Cargo builds, unit tests, static analysis, and CI.

### 12 Months

- Demonstrate an end-to-end industrial edge system: sensors, protocol gateway, local persistence, monitoring, and recovery.
- Publish measured resource use, timing, and fault behavior for key embedded projects.
- Maintain reusable C++ and Rust components for networking, protocols, and telemetry.

## Tech Stack

- **Languages:** C++, Rust, C, Python, Dart
- **Platforms:** Raspberry Pi 5, ESP32, STM32, embedded Linux
- **Build & Test:** CMake, Cargo, unit testing, GitHub Actions
- **Protocols:** Wi-Fi, HTTP, MQTT, CAN/SocketCAN, Modbus RTU/TCP, serial
- **Sensors & Media:** GPS, IMU, barometer, environmental sensors, RTSP cameras
- **Operations:** systemd, Docker where appropriate, structured logging, watchdogs

## Articles

| Working title | Project connection | Status |
| --- | --- | --- |
| Designing a Recoverable Headless Wi-Fi Provisioning State Machine | Wi-Fi provisioning projects | Planned |
| From ESP32 Sensors to a Tablet Telemetry Interface | `skyvision-control-case-study` | Planned |
| Testing CAN Software Without a Vehicle Using Virtual CAN | `can-bus-diagnostics-tool` | Planned |
| Building a Rust Modbus-to-MQTT Gateway with Failure Recovery | `modbus-iot-gateway` | Planned |

Medium links will be added after publication.

## Career Target

This portfolio supports applications for:

- Embedded Software Engineer
- Embedded Linux Engineer
- IoT / Edge Systems Engineer
- C++ Software Engineer for device or industrial systems
- Rust Systems Engineer at an early-career or applied level
- Industrial Automation Software Engineer

The portfolio will emphasize code, interfaces, timing, recovery behavior, protocol knowledge, and measured hardware constraints.

## Status

- **Completed:** reproducible scope delivered and documented
- **In Progress:** implementation exists, but validation or portfolio evidence remains
- **Planned:** proposal only; not presented as completed experience
- **Learning:** study material that supports the track but is not a flagship project

**Portfolio status: In Progress**

## Connect

- [Medium](https://medium.com/@sirvanksc)
- [LinkedIn](https://www.linkedin.com/in/srvnksc/)
- [YouTube](https://www.youtube.com/@SirvanKesici)
