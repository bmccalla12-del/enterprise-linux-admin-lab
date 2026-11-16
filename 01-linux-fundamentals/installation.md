# Lab 01: Red Hat Enterprise Linux 10 Installation

## 1. Objective

The objective of this lab was to deploy a Red Hat Enterprise Linux 10 virtual machine using Oracle VirtualBox.

This lab establishes the foundation for learning Linux system administration and preparing for the RHCSA certification.

## 2. Hardware Environment

| Component | Specification |
|---|---|
| Laptop | Dell Inspiron 3501 |
| Processor | Intel Core i5-1035G1 |
| CPU Cores | 4 |
| RAM | 8 GB |
| Storage | 256 GB SSD |
| Host OS | Windows 11 |

## 3. Virtual Machine Configuration

| Component | Configuration |
|---|---|
| Hypervisor | Oracle VirtualBox 7.2.22 |
| Guest OS | RHEL 10.0 |
| CPU Allocation | 2 cores |
| Memory Allocation | 3 GB |
| Virtual Disk | 30 GB |
| Disk Format | VDI |
| Disk Allocation | Dynamically allocated |
| Network | NAT |

## 4. Installation Process

The following tasks were completed:

- [x] Installed Oracle VirtualBox.
- [x] Downloaded RHEL 10 installation ISO.
- [x] Created virtual machine.
- [x] Configured virtual CPU and memory.
- [x] Created 30 GB virtual hard disk.
- [x] Configured NAT networking.
- [x] Installed RHEL 10.0.
- [x] Created administrator account.
- [x] Successfully booted into RHEL.

## 5. Troubleshooting

### Installation Source Error

**Problem:** The initial installation failed to configure the installation source.

**Cause:** The initial ISO was the Boot ISO, which required a network installation repository.

**Resolution:** Downloaded the full DVD installation ISO and attached it to the virtual machine.

**Result:** Successfully installed RHEL 10.0.

## 6. Key Concepts Learned

- Virtualization allows multiple operating systems to run on one physical computer.
- VirtualBox provides virtual hardware for guest operating systems.
- Dynamically allocated storage grows as the virtual machine uses disk space.
- NAT allows the virtual machine to access external networks through the host.
- RHEL uses the Anaconda installer to configure the operating system.

## 7. Next Steps

- Learn Linux command-line fundamentals.
- Explore the Linux filesystem hierarchy.
- Practice file and directory management.
- Learn user and group administration.
- Begin RHCSA objective-based exercises.

## 8. References

- Red Hat Documentation: https://docs.redhat.com/
- VirtualBox Documentation: https://www.virtualbox.org/manual/
- RHCSA Certification: https://www.redhat.com/en/services/training/ex200-red-hat-certified-system-administrator-rhcsa-exam
