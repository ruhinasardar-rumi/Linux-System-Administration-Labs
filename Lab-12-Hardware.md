# Lab 12: Hardware & System Information

## Objective

Audit and report system hardware architecture, CPU capabilities, memory distribution, and connected peripherals.

---

## System Auditing Commands

### 1. CPU & Memory
- Queried processor specs with `lscpu`.
- Evaluated active memory allocation and swap space using `free -h`.

### 2. Device Hardware
- Enumerated PCI devices with `lspci` and USB interfaces with `lsusb`.
- Verified active disk partitions and storage devices using `fdisk -l` and `lsblk`.
