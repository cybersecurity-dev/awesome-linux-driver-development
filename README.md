<div align="center">
    <p align="center">
        <a href="https://wikipedia.org/wiki/Category:Linux_drivers">
          <img width="10%" src="https://github.com/cybersecurity-dev/cybersecurity-dev/blob/main/assets/Tux.svg" />
        </a>
    </p>

# `Awesome` [Linux](https://wikipedia.org/wiki/Linux_kernel_interfaces) [Driver](https://wikipedia.org/wiki/Driver_(software)) [Development](https://wikipedia.org/wiki/Device_driver) [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
</div>

[![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)](https://wikipedia.org/wiki/Linux_kernel_version_history)
[![YouTube](https://img.shields.io/badge/YouTube-%23FF0000.svg?style=for-the-badge&logo=YouTube&logoColor=white)](https://youtube.com/playlist?list=PL9V4Zu3RroiU9ZlPeiXjNTB_mCFsOeduk&si=_ji5HJWktP3IRnBw)
[![Reddit](https://img.shields.io/badge/Reddit-FF4500?style=for-the-badge&logo=reddit&logoColor=white)](https://www.reddit.com/r/kernel/)

<p align="center">
    <a href="https://github.com/cybersecurity-dev/"><img height="25" src="https://github.com/cybersecurity-dev/cybersecurity-dev/blob/main/assets/github.svg" alt="GitHub"></a>
    &nbsp;
    <a href="https://www.youtube.com/@CyberThreatDefense"><img height="25" src="https://github.com/cybersecurity-dev/cybersecurity-dev/blob/main/assets/youtube.svg" alt="YouTube"></a>
    &nbsp;
    <a href="https://cyberthreatdefence.com/my_awesome_lists"><img height="20" src="https://github.com/cybersecurity-dev/cybersecurity-dev/blob/main/assets/blog.svg" alt="My Awesome Lists"></a>
</p>

```mermaid
flowchart TD

    A[Programming Fundamentals]

    A --> A1[C Programming]
    A --> A2[Pointers]
    A --> A3[Structures & Unions]
    A --> A4[Bitwise Programming]

    A4 --> B[Computer Architecture]

    B --> B1[x86 / ARM Architecture]
    B --> B2[Memory Hierarchy]
    B --> B3[Assembly Language]
    B --> B4[CPU Privilege Levels]
    B --> B5[Interrupts & Exceptions]

    B5 --> C[Operating Systems]

    C --> C1[Processes & Threads]
    C --> C2[Scheduling]
    C --> C3[Virtual Memory]
    C --> C4[Synchronization]
    C --> C5[File Systems]

    C5 --> D[Linux Fundamentals]

    D --> D1[Bash]
    D --> D2[Linux Commands]
    D --> D3[System Calls]
    D --> D4[Procfs]
    D --> D5[Sysfs]
    D --> D6[udev]

    D6 --> E[Linux Kernel Basics]

    E --> E1[Kernel Architecture]
    E --> E2[Kernel Source Tree]
    E --> E3[Kernel Build System]
    E --> E4[Kconfig]
    E --> E5[Kbuild]
    E --> E6[Kernel Boot Process]

    E6 --> F[Kernel Programming]

    F --> F1[Loadable Kernel Modules]
    F --> F2[Kernel APIs]
    F --> F3[Memory Allocation]
    F --> F4[Kernel Data Structures]

    F4 --> G[Driver Development]

    G --> G1[Character Drivers]
    G --> G2[Block Drivers]
    G --> G3[Network Drivers]
    G --> G4[PCI Drivers]
    G --> G5[USB Drivers]
    G --> G6[I2C Drivers]
    G --> G7[SPI Drivers]
    G --> G8[Platform Drivers]

    G8 --> H[Hardware Interaction]

    H --> H1[MMIO]
    H --> H2[Port I/O]
    H --> H3[DMA]
    H --> H4[Interrupt Handling]
    H --> H5[Device Tree]

    H5 --> I[Driver Interfaces]

    I --> I1[ioctl]
    I --> I2[sysfs]
    I --> I3[procfs]
    I --> I4[mmap]
    I --> I5[netlink]

    I5 --> J[Synchronization]

    J --> J1[Spinlocks]
    J --> J2[Mutexes]
    J --> J3[Semaphores]
    J --> J4[Completions]
    J --> J5[RCU]

    J5 --> K[Debugging & Profiling]

    K --> K1[printk]
    K --> K2[dmesg]
    K --> K3[ftrace]
    K --> K4[perf]
    K --> K5[kgdb]
    K --> K6[crash]
    K --> K7[eBPF]

    K7 --> L[Advanced Topics]

    L --> L1[Power Management]
    L --> L2[Kernel Security]
    L --> L3[LSM Framework]
    L --> L4[Hotplug]
    L --> L5[Networking Stack]
    L --> L6[Driver Frameworks]

    L6 --> M[Kernel Contribution]

    M --> M1[Git]
    M --> M2[checkpatch.pl]
    M --> M3[Patch Development]
    M --> M4[Kernel Coding Style]
    M --> M5[Mailing Lists]
    M --> M6[Maintainer Review]

    M6 --> N[Professional Linux Driver Developer]

    style A fill:#0b5394,stroke:#073763,color:#ffffff
    style B fill:#3d85c6,stroke:#0b5394,color:#ffffff
    style C fill:#6aa84f,stroke:#38761d,color:#ffffff
    style D fill:#674ea7,stroke:#351c75,color:#ffffff
    style E fill:#e69138,stroke:#b45f06,color:#ffffff
    style F fill:#f1c232,stroke:#bf9000,color:#000000
    style G fill:#990000,stroke:#660000,color:#ffffff
    style H fill:#008080,stroke:#005555,color:#ffffff
    style I fill:#8e7cc3,stroke:#674ea7,color:#ffffff
    style J fill:#cc4125,stroke:#990000,color:#ffffff
    style K fill:#6fa8dc,stroke:#0b5394,color:#ffffff
    style L fill:#38761d,stroke:#274e13,color:#ffffff
    style M fill:#434343,stroke:#222222,color:#ffffff
    style N fill:#000000,stroke:#000000,color:#ffffff
```

## 📖 Contents
- [My Other Awesome Lists](#my-other-awesome-lists)
- [Contributing](#contributing)
- [Contributors](#contributors)


In Linux, drivers are categorized based on the type of device or functionality they manage. 
* The device driver types are:
    * [Character Device](https://linux-kernel-labs.github.io/refs/heads/master/labs/device_drivers.html)
    * [Block Device](https://linux-kernel-labs.github.io/refs/heads/master/labs/block_device_drivers.html)
    * [Network Device](https://linux-kernel-labs.github.io/refs/heads/master/labs/networking.html)
* Other Drivers
    * File System Drivers
    * Virtual Drivers
    * Platform Drivers
    * Pseudo Drivers
    * User-Space Drivers

## 1. [Kernel](https://linux-kernel-labs.github.io/refs/heads/master/)-Space Driver

### 1.1 Device [Driver](https://www.kernel.org/doc/html/v6.16/driver-api/index.html)

#### Programming Guide
- [Tutorial for Linux Driver Development](https://www.apriorit.com/dev-blog/195-simple-driver-for-linux-os)

### 1.2 [Kernel](https://docs.redhat.com/en/documentation/red_hat_enterprise_linux/7/html/kernel_administration_guide) [Module](https://en.wikipedia.org/wiki/Loadable_kernel_module)

#### Programming Guide
 - [Linux Kernel Module](https://github.com/sysprog21/lkmpg) - The Linux Kernel Module [Programming](https://sysprog21.github.io/lkmpg) Guide

## 2. [User-Space](https://en.wikipedia.org/wiki/User_space_and_kernel_space) Driver

## 3. Miscellaneous
- [https://lxr.linux.no/](https://lxr.linux.no/) - Linux source code repositories.
- [https://elixir.bootlin.com/](https://elixir.bootlin.com/linux) - Linux source code repositories.
- [https://kernelnewbies.org/](https://kernelnewbies.org/)
- [https://www.kernel.org/doc/html/latest/](https://www.kernel.org/doc/html/latest/)
- [https://lwn.net/](https://lwn.net/)
- [https://embetronicx.com/](https://embetronicx.com/)

##
### My Other Awesome Lists
You can access the my other awesome lists [here](https://cyberthreatdefence.com/my_awesome_lists)

### Contributing
[Contributions of any kind welcome, just follow the guidelines](contributing.md)!

### Contributors
[Thanks goes to these contributors](https://github.com/cybersecurity-dev/awesome-linux-driver-development/graphs/contributors)!

### License
[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](http://creativecommons.org/publicdomain/zero/1.0)

[🔼 Back to top](#awesome-linux-driver-development-)
