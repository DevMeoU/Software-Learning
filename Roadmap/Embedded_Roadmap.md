# Lộ trình Kỹ thuật Hệ thống Nhúng

Lộ trình này được tạo dựa trên [Embedded Systems Engineering Roadmap by m3y54m](https://github.com/m3y54m/Embedded-Engineering-Roadmap).

**Chú giải:**

* `[R]` - Bắt buộc (Required)
* `[Re]` - Khuyến nghị (Recommended)
* `[P]` - Có thể (Possibilities)

## ĐIỂM BẮT ĐẦU

### PHẦN CỨNG (HARDWARE)

#### Điện tử (Electronics)

- [ ] `[R]` Toán & Giải tích cơ bản (Basic Math & Calculus)
- [ ] `[R]` Nguyên lý Mạch điện (Principles of Electric Circuits)
- [ ] `[R]` Kiến thức cơ bản về Điện tử (Electronics Fundamentals)
- [ ] `[R]` Thiết kế số (Digital Design)
- [ ] `[Re]` Kiến trúc Máy tính (Computer Architecture)

#### Sử dụng Thiết bị Kiểm tra (Using Test Equipment)

- [ ] `[R]` Đồng hồ vạn năng (Multimeter)
- [ ] `[R]` Bộ phân tích Logic / Giao thức (Logic / Protocol Analyzer)
- [ ] `[R]` Máy hiện sóng (Oscilloscope)

#### Kỹ năng Tạo mẫu (Prototyping Skills)

- [ ] `[R]` Breadboarding
- [ ] `[Re]` Kiến thức cơ bản về Thiết kế Phần cứng (Hardware Design Basics)
- [ ] `[Re]` Thiết kế PCB / EMC (PCB Design / EMC)
- [ ] `[Re]` Hàn / Sửa chữa (Soldering / Rework)

#### Phát triển FPGA (FPGA Development)

- [ ] `[P]` FPGA Development

### PHẦN MỀM (SOFTWARE)

#### Ngôn ngữ Lập trình (Programming Languages)

- [X] `[R]` C
- [X] `[R]` C++
- [X] `[Re]` Python
- [X] `[Re]` Assembly
- [ ] `[P]` Rust

#### Kiến thức cơ bản về Lập trình (Programming Fundamentals)

- [ ] `[R]` Thuật toán & Cấu trúc Dữ liệu (Algorithms & Data Structures)
- [ ] `[Re]` Mẫu Thiết kế (Design Patterns)
- [ ] `[Re]` Máy trạng thái (State Machines)
- [ ] `[R]` Quản lý Bộ nhớ (Memory Management)

#### Hệ điều hành (Operating Systems)

- [ ] `[R]` **Kiến thức cơ bản về Hệ điều hành (Operating System Fundamentals)**
- [ ] `[Re]` **Linux nhúng (Embedded Linux)**
  - [ ] Nhân Linux (Linux Kernel)
  - [ ] Trình điều khiển Thiết bị (Device Drivers)
  - [ ] U-Boot
  - [ ] Buildroot / Yocto
- [ ] `[R]` **Hệ điều hành Thời gian thực (Real-Time OS - RTOS)**
  - [X] Kiến thức cơ bản về RTOS (RTOS Basics)
  - [ ] FreeRTOS
  - [ ] Zephyr
  - [ ] QNX
  - [ ] µC/OS
  - [ ] RT-Thread
- [ ] `[Re]` Luồng / Song song (Threading / Parallelism)
- [ ] `[Re]` Giao tiếp Liên tiến trình (IPC - Inter-Process Communication)
- [ ] `[P]` Qt Framework

#### Vi điều khiển (Microcontrollers)

- [X] `[R]` GPIO
- [X] `[R]` ADC / DAC
- [X] `[R]` Bộ định thời / Bộ đếm (Timers / Counters)
- [X] `[R]` PWM (Pulse Width Modulation)
- [ ] `[R]` Watchdog
- [X] `[R]` Ngắt (Interrupts)
- [ ] `[R]` DMA (Direct Memory Access)
- [ ] `[R]` Quản lý Đồng hồ (Clock Management)
- [ ] `[R]` Quản lý Nguồn (Power Management)
- [ ] `[R]` Bootloader / DFU (Device Firmware Update)

#### Giao diện & Giao thức (Interfaces & Protocols)

- [X] **Cơ bản (Basic)**
  - [X] `[R]` UART
  - [ ] `[R]` I2C
  - [ ] `[R]` SPI
- [ ] **Tốc độ cao (High-Speed)**
  - [ ] `[Re]` Ethernet
  - [ ] `[Re]` USB
  - [ ] `[Re]` PCIe
- [ ] **Không dây (Wireless)**
  - [ ] `[Re]` Bluetooth
  - [ ] `[Re]` Wi-Fi
  - [ ] `[Re]` LoRa
  - [ ] `[Re]` Zigbee
  - [ ] `[Re]` Thread
  - [ ] `[Re]` Matter
  - [ ] `[Re]` UWB (Ultra-Wideband)
- [ ] **Công nghiệp (Industrial)**
  - [ ] `[Re]` Modbus
  - [ ] `[Re]` Profinet
  - [ ] `[Re]` EtherCAT
  - [ ] `[Re]` MQTT
  - [ ] `[Re]` CoAP
- [ ] **Mạng (Network)**
  - [ ] `[R]` TCP/IP
  - [ ] `[R]` UDP
- [ ] **Ô tô (Automotive)**
  - [ ] `[P]` CAN
  - [ ] `[P]` LIN
  - [ ] `[P]` MOST
  - [ ] `[P]` FlexRay
- [ ] **Di động (Cellular)**
  - [ ] `[P]` GSM / LTE
  - [ ] `[P]` LTE-M / 5G
  - [ ] `[P]` NB-IoT

#### Công nghệ Bộ nhớ & Hệ thống Tệp (Memory Technologies & File Systems)

- [ ] `[Re]` Memory Technologies & File Systems

#### Mô phỏng / Giả lập Phần cứng (Hardware Simulation / Emulation)

- [ ] `[Re]` Hardware Simulation / Emulation

#### Mô hình Vòng đời Phát triển Phần mềm (SDLC Models)

- [ ] `[Re]` Agile / SCRUM
- [ ] `[Re]` V-Model

#### Hệ thống Xây dựng (Build System)

- [X] `[R]` Trình biên dịch / GCC (Compilers / GCC)
- [X] `[R]` Make / CMake
- [X] `[Re]` Bash Scripting
- [X] `[P]` Docker

#### Gỡ lỗi (Debugging)

- [X] `[R]` JTAG / SWD
- [X] `[R]` GDB (GNU Debugger)
- [ ] `[Re]` OpenOCD

#### Kiểm thử (Testing)

- [ ] `[Re]` TDD & Kiểm thử Đơn vị (TDD & Unit Testing)
- [ ] `[Re]` CI/CD Pipelines
- [ ] `[Re]` Kiểm thử SIL / HIL (SIL / HIL Testing)
- [ ] `[Re]` Tiêu chuẩn & Chứng nhận (Standards & Certifications)

#### Bảo mật Nhúng (Embedded Security)

- [ ] `[Re]` Embedded Security

#### Giao diện Người dùng Nhúng (Embedded GUI)

- [ ] `[P]` Embedded GUI

#### IoT (Internet of Things)

- [X] `[Re]` IoT

#### AI Biên (Edge AI)

- [ ] `[P]` Edge AI

#### AUTOSAR

- [X] `[P]` AUTOSAR

#### Cảm biến & Cơ cấu Chấp hành (Sensors & Actuators)

- [X] `[Re]` Sensors & Actuators

#### Xử lý Tín hiệu Số (Digital Signal Processing)

- [X] `[Re]` Digital Signal Processing

#### Lý thuyết Điều khiển (Control Theory)

- [ ] `[Re]` Control Theory

### KỸ NĂNG MỀM (SOFT SKILLS)

- [X] `[R]` Kỹ năng Giao tiếp (Communication Skills)
- [X] `[R]` Kỹ năng Giải quyết Vấn đề & Tư duy Phản biện (Problem-Solving Skills & Critical Thinking)
- [X] `[R]` Kỹ năng Làm việc Nhóm & Hợp tác (Teamwork & Collaborative Abilities)
- [ ] `[R]` Kỹ năng Tổ chức & Quản lý Thời gian (Organizational & Time Management Skills)
- [ ] `[R]` Tự giác & Độc lập (Being Self-Driven and Independent)
- [ ] `[R]` Khả năng Thích ứng & Kiên nhẫn (Adaptability & Patience)

## CÁC NGÀNH MỤC TIÊU

* Điện tử Tiêu dùng (Consumer Electronics)
* Viễn thông (Telecommunications)
* Ô tô (Automotive)
* Chăm sóc Sức khỏe (Healthcare)
* Nông nghiệp (Agriculture)
* Robot (Robotics)
* Hàng không Vũ trụ (Aerospace)
* ...
