# Day 01 — Linux Fundamentals 🐧

## Objective

Build a strong foundation in Linux and understand how
Linux is used by DevOps engineers.

---

# 1. What is Linux?

Linux is an open-source kernel that manages system
resources such as CPU, memory, processes, storage,
networking and devices.

A complete Linux distribution combines the Linux kernel
with utilities, libraries, package management and other
software.

---

# 2. Linux Kernel

The kernel is the core component of Linux.

It manages:

- CPU
- Memory
- Processes
- Filesystems
- Networking
- Devices
- Security

Basic architecture:

User
↓
Application
↓
Shell
↓
System Calls
↓
Linux Kernel
↓
Hardware

---

# 3. Linux Distributions

Examples of Linux distributions:

- Ubuntu
- Debian
- Fedora
- RHEL
- Rocky Linux
- Amazon Linux

Ubuntu is a Linux distribution built around the Linux
kernel.

---

# 4. Terminal vs Shell

## Terminal

A terminal provides an interface through which a user
can interact with the system.

## Shell

A shell interprets commands and starts programs.

Examples:

- Bash
- Zsh
- Fish
- Sh

---

# 5. Bash

Bash stands for:

Bourne Again Shell

Bash is commonly used on Linux and is important for
automation and DevOps scripting.

---

# 6. CLI

CLI means:

Command Line Interface

DevOps engineers use CLI heavily because Linux servers
are commonly managed remotely through tools such as SSH.

---

# 7. Program vs Process

A program is executable code stored on the system.

A process is a running instance of a program.

Example:

Program
↓
Start
↓
Process
↓
PID

---

# 8. Linux Filesystem Hierarchy

Linux has a single filesystem hierarchy beginning at:

/

Important directories:

| Directory | Purpose |
|---|---|
| `/` | Root of the filesystem |
| `/etc` | System and application configuration |
| `/var` | Variable data |
| `/var/log` | Logs |
| `/home` | Normal user home directories |
| `/root` | Root user's home directory |
| `/tmp` | Temporary files |
| `/usr` | Programs and system resources |
| `/proc` | Process and kernel information |
| `/sys` | Kernel and device information |
| `/dev` | Device files |
| `/run` | Runtime system information |
| `/boot` | Boot-related files |
| `/opt` | Optional/third-party software |
| `/mnt` | Mount point |

---

# 9. Important Difference

## `/`

The root directory of the entire Linux filesystem.

## `/root`

The home directory of the root user.

They are NOT the same thing.

---

# 10. Commands Practiced

```bash
whoami
id
pwd
hostname
uname -a
date
uptime
ls
ls -l
ls -a
cd
df -h
