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

## Side Projects

Things I build outside work:

- **Motor control:** FOC for PMSM in bare-metal C: discrete PI controllers, SVPWM, and voltage vector clamping.
- **Power electronics:** Bidirectional buck-boost DC-DC converter for battery charge and discharge, with current and voltage control.
- **Digital twins:** ECU digital twins in Unity, connected to CANoe, to simulate network behavior and physical responses in real time.
- **Robotics:** ROS 2, kinematics (quaternions, transformation matrices, inverse kinematics), trajectories, and Newton-Euler / Lagrangian dynamics.
- **Retro and systems:** Bare-metal PS1 programming in MIPS assembly and C, Android AOSP, compilers, and interpreters.

I also experiment with DevOps, quantum computing, and cyber security.

## Repositories

Some of what you can find on my GitHub right now:

- **Microcontrollers:** CMake build systems for TI C2000 and STM32, a layered architecture that keeps applications independent of the MCU, and SPI display drivers on STM32.
- **Embedded Rust:** Bare-metal Rust projects on STM32F4 boards, built from scratch.
- **Embedded Linux:** Yocto on the Raspberry Pi 5, a BeagleBone Black development image, and a kernel module.
- **Containers:** Docker toolchains for bare metal, FreeRTOS, Zephyr, Linux, and ROS 2.
- **Graphics and games:** A 2D game engine in C++ with SDL and Lua scripting, a Dear ImGui app template, and a Unity mobile game.
- **AI engineering:** Notebooks, LangChain agents, and an AI workflow that refactors Obsidian notes.
- **Tooling:** My Emacs, Neovim, and Vim setups, C++ project templates, and data structures and algorithms practice.

I will keep adding to this list and make more of my work public over time.

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
- **Udemy** - targeted courses on embedded, C/C++, and operating systems
- **Packt and Leanpub** - technical books and deep-dive engineering literature
