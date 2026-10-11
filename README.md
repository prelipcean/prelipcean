# Hi, I'm a Systems & Embedded Software Engineer

I have more than ten years of experience connecting low-level electronics, mechanics, and modern software architecture. I build reliable, mission-critical systems from scratch, starting from first principles. My background is in automotive, but the same methods carry over to space, defense, and medical technology.

I like reverse engineering, building proof-of-concepts, cutting costs, and finding the "needle in a haystack" in hard cross-domain bugs.

## Current Role

Embedded Software Engineer in automotive.

- Develop low-level drivers (MCAL and peripheral drivers) and application software for automotive ECUs.
- Configure AUTOSAR BSW and MCAL modules with EB Tresos.
- Debug on target at the chip and compiler level with hardware debuggers, oscilloscopes, logic analyzers, and CAN bus analysis.

## Skills

- **Languages:** C (professional), C++ and C# (working), Rust (foundational), Python, Bash, ARM / MIPS / AVR / RISC-V assembly
- **RTOS and platforms:** FreeRTOS, Zephyr, Keil RTX (CMSIS-RTOS), AUTOSAR / OSEK, Linux and Yocto bring-up
- **Embedded Linux:** Kernel modules, Yocto, Buildroot, U-Boot, Device Tree
- **Architecture:** SOLID, MISRA C, system-level design, DSP, fixed-point math, speed optimization
- **Control theory:** PID, MPC, bang-bang, sliding mode control and observers, Extended Kalman Filter
- **Motor control:** BLDC, FOC, SVPWM, high-frequency injection, Park/Clarke transforms
- **Interfaces:** CAN, SPI, I2C, UART, USB, Ethernet, BLE, custom protocols
- **Build and tooling:** CMake, Make, Ninja, West, Kconfig, Docker, CI/CD
- **Environment:** Terminal first on Linux, macOS, and Windows. Vim, Emacs, Bash.

## How I Work

- **Low level first:** Know the CPU architecture and control the memory layout with custom linker scripts.
- **Simulate before flashing:** Digital twins, QEMU, and network simulations catch edge cases early.
- **Own the build:** Reproducible multi-platform builds with tightly managed dependencies.

## Side Projects and Tinkering

Things I build outside work:

- **Motor control:** FOC for PMSM in bare-metal C: discrete PI controllers, SVPWM, and voltage vector clamping.
- **Power electronics:** A bidirectional buck-boost DC-DC converter that charges and discharges a battery, with current and voltage control loops and switching between charge and discharge modes.
- **Digital twins:** ECU digital twins in Unity, connected to CANoe, to simulate network behavior and physical responses in real time.
- **Robotics:** ROS 2, kinematics (quaternions, transformation matrices, inverse kinematics), trajectories, and Newton-Euler / Lagrangian dynamics.
- **Retro and systems:** Bare-metal PS1 programming in MIPS assembly and C, Android AOSP, compilers, interpreters, and game engines.
- **Tooling:** A modular Emacs setup (LSP, Magit, PlantUML) for C/C++ embedded work.

I also experiment with AI engineering, DevOps, quantum computing, and cyber security.

## Repositories

**Microcontrollers (C)**
- [TI_LaunchPad_C2000_F28069M](https://github.com/prelipcean/TI_LaunchPad_C2000_F28069M) - CMake build system for the TI C2000 F28069M
- [STM32_CMake_Example](https://github.com/prelipcean/STM32_CMake_Example) - CMake build for STM32 projects in C, C++, and assembly
- [demo_project_f446re](https://github.com/prelipcean/demo_project_f446re) - layered architecture that decouples applications from the MCU (STM32F446RE)
- [SPI_LCD_TestPattern](https://github.com/prelipcean/SPI_LCD_TestPattern) - LCD test patterns over SPI on the STM32F446RE

**Embedded Rust**
- [stm32f429_blinky](https://github.com/prelipcean/stm32f429_blinky) - bare-metal Rust on the STM32F429
- [STM_F446RE_Rust](https://github.com/prelipcean/STM_F446RE_Rust) - Rust on the STM32F446RE from scratch

**Embedded Linux and containers**
- [embedded-dev-containers](https://github.com/prelipcean/embedded-dev-containers) - toolchain containers for bare metal, FreeRTOS, Zephyr, and Linux
- [rpi5_yocto_study](https://github.com/prelipcean/rpi5_yocto_study) - Yocto on the Raspberry Pi 5
- [docker_dev_bbbw](https://github.com/prelipcean/docker_dev_bbbw) - development image for the BeagleBone Black Wireless
- [hello_module](https://github.com/prelipcean/hello_module) - a minimal Linux kernel module
- [ros2-jazzy-docker](https://github.com/prelipcean/ros2-jazzy-docker) - ROS 2 Jazzy in Docker

**Graphics, games, and C++**
- [GameEngine_2D_2026](https://github.com/prelipcean/GameEngine_2D_2026) - 2D game engine with SDL, C++, and Lua scripting
- [app_template_imgui](https://github.com/prelipcean/app_template_imgui) - C++ Dear ImGui template for small tools
- [CMakeCPPTemplate](https://github.com/prelipcean/CMakeCPPTemplate) - CMake template for C++ projects
- [dsa](https://github.com/prelipcean/dsa) - data structures and algorithms in C++
- [UnityCasualProject-CarrotClicker](https://github.com/prelipcean/UnityCasualProject-CarrotClicker) - idle clicker mobile game in Unity

**AI engineering**
- [ai-engineering-codespace](https://github.com/prelipcean/ai-engineering-codespace) - AI engineering notebooks
- [CreateAgents](https://github.com/prelipcean/CreateAgents) - agents with LangChain
- [obsidian-ai-refactor](https://github.com/prelipcean/obsidian-ai-refactor) - refactoring Obsidian notes with AI agents

**Editor and system setup**
- [emacs_cfg](https://github.com/prelipcean/emacs_cfg) - modular Emacs configuration
- [nvim_setup](https://github.com/prelipcean/nvim_setup) - Neovim as an IDE
- [vim](https://github.com/prelipcean/vim) - Vim configuration
- [arch_linux_journey](https://github.com/prelipcean/arch_linux_journey) - notes from setting up Arch Linux

## Reading and Learning

**Firmware and architecture**
- [Interrupt by Memfault](https://interrupt.memfault.com/) - firmware, debugging, observability
- [Embedded Artistry](https://embeddedartistry.com/blog/) - design patterns and build systems
- [Beningo Embedded Group](https://www.beningo.com/) - embedded architecture and RTOS
- [Jack Ganssle](https://www.ganssle.com/) - reliability and testing
- [PyjamaBrah](https://pyjamabrah.com/) - ARM Cortex-M/A courses

**Linux kernel and systems**
- [Bootlin](https://bootlin.com/blog/) - kernel, BSPs, toolchains
- [LWN.net](https://lwn.net/) - Linux kernel news

**Courses and books**
- Nand2Tetris (Coursera) - from logic gates to a compiler and a custom CPU
- [Pikuma](https://pikuma.com/) - emulators, compilers, physics engines
- Udemy, Packt, Leanpub
