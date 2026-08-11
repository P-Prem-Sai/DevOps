# Linux

Linux is one of the fundamental technologies for DevOps, cloud computing, containers, system administration, and backend engineering.

The goal of this section is to develop a strong understanding of Linux from the fundamentals to advanced system concepts, with a particular focus on **practical usage, troubleshooting, production systems, and DevOps**.

---

## Learning Objectives

By the end of this section, I should be able to:

* Understand Linux architecture and how the Linux kernel works.
* Navigate and manage the Linux filesystem efficiently.
* Use essential Linux commands confidently.
* Understand users, groups, ownership, and permissions.
* Manage processes, jobs, and system resources.
* Write and understand Bash scripts.
* Install and manage software packages.
* Understand Linux networking and troubleshoot network issues.
* Manage disks, filesystems, mounts, and storage.
* Manage Linux services using `systemd`.
* Read and analyze system and application logs.
* Understand important Linux internals such as processes, memory, filesystems, and system calls.
* Troubleshoot common Linux problems.
* Understand advanced Linux security and access-control mechanisms.
* Diagnose production issues using advanced tracing and monitoring tools.
* Understand kernel configuration and performance tuning.
* Understand Linux concepts required for Docker, Kubernetes, and cloud environments.

---

# Core Linux

The following topics form the **core Linux foundation** and should be completed first.

## Topics

### 1. Linux Fundamentals

Learn the basic concepts required to understand Linux.

* What is Linux?
* Linux kernel
* Operating system vs kernel
* Linux distributions
* Linux architecture
* Shell and terminal
* System calls
* Linux filesystem hierarchy
* Absolute and relative paths
* Linux directory structure

[Learn Linux Fundamentals →](./01-linux-fundamentals/README.md)

---

### 2. Essential Linux Commands

Learn the commands used for everyday Linux administration and development.

* Navigation
* File and directory management
* Viewing files
* Searching
* Text processing
* Pipes
* Input/output redirection
* Command history
* Command substitution
* Useful command combinations

Important commands include:

```bash
pwd
ls
cd
cp
mv
rm
mkdir
touch
cat
less
head
tail
find
grep
sort
uniq
cut
awk
sed
wc
xargs
```

[Learn Essential Commands →](./02-essential-commands/README.md)

---

### 3. Files, Users & Permissions

Understand Linux's security and access-control model.

* Users
* Groups
* File ownership
* Read/write/execute permissions
* `chmod`
* `chown`
* `chgrp`
* `umask`
* SUID
* SGID
* Sticky bit
* `/etc/passwd`
* `/etc/group`
* `/etc/shadow`

[Learn Files & Permissions →](./03-files-and-permissions/README.md)

---

### 4. Processes & Jobs

Understand how Linux executes and manages programs.

* Process vs program
* Process IDs
* Parent and child processes
* Process states
* Threads
* Signals
* Foreground and background processes
* Job control
* Process priorities

Important commands:

```bash
ps
top
htop
kill
pkill
jobs
bg
fg
nice
renice
```

[Learn Processes →](./04-processes/README.md)

---

### 5. Shell & Bash

Learn how to automate Linux tasks using the shell.

* Bash fundamentals
* Variables
* Environment variables
* `$PATH`
* Quoting
* Conditions
* Loops
* Functions
* Exit codes
* Command-line arguments
* Pipes and redirection
* Shell scripting
* Debugging Bash scripts

[Learn Shell & Bash →](./05-shell-and-bash/README.md)

---

### 6. Package Management

Understand how software is installed and managed in Linux.

* Packages
* Repositories
* `apt`
* `dpkg`
* Package installation
* Package removal
* Package updates
* Dependencies
* Repository configuration

[Learn Package Management →](./06-package-management/README.md)

---

### 7. Linux Networking

Understand how Linux communicates over networks.

* Network interfaces
* IP addresses
* MAC addresses
* Routing
* Ports
* TCP/UDP
* DNS
* DHCP
* localhost
* Sockets
* SSH
* Network troubleshooting

Important commands:

```bash
ip
ss
ping
curl
wget
dig
nslookup
traceroute
ssh
scp
```

[Learn Linux Networking →](./07-networking/README.md)

---

### 8. Storage & Filesystems

Understand how Linux manages disks and storage.

* Disks
* Partitions
* Filesystems
* Mounting
* Unmounting
* Disk usage
* Inodes
* `/etc/fstab`
* `df`
* `du`
* `lsblk`
* LVM basics

[Learn Storage & Filesystems →](./08-storage/README.md)

---

### 9. Services & System Management

Learn how Linux starts, manages, and monitors services.

* Boot process
* `systemd`
* Services
* `systemctl`
* `journalctl`
* Service configuration
* Startup services
* Logs
* Timers
* Cron jobs

[Learn System Management →](./09-system-management/README.md)

---

### 10. Linux Internals

Go deeper into how Linux works internally.

* Linux kernel
* System calls
* Processes
* Threads
* CPU scheduling
* Memory management
* Virtual memory
* File descriptors
* Filesystems
* `/proc`
* `/sys`
* Signals
* Inter-process communication
* Context switching

[Learn Linux Internals →](./10-linux-internals/README.md)

---

### 11. Linux for DevOps

Apply Linux knowledge to real-world DevOps environments.

* SSH
* Remote server administration
* Environment variables
* Application deployment
* Log analysis
* Resource monitoring
* Service management
* Process troubleshooting
* Network troubleshooting
* Cron automation
* Shell automation
* Linux security basics
* Containers
* Namespaces
* cgroups
* Linux and Docker
* Linux and Kubernetes

[Learn Linux for DevOps →](./11-linux-for-devops/README.md)

---

# Advanced & Production Linux

After completing the core topics, continue with the following advanced topics.

These topics are especially useful for **production troubleshooting, system administration, containers, Kubernetes, security, and performance engineering**.

### 12. Advanced Diagnostics & Tracing

Learn how to investigate problems that cannot be diagnosed using basic tools such as `top` and `htop`.

* `strace`
* System call tracing
* `sysstat`
* `iostat`
* `sar`
* CPU analysis
* Disk I/O analysis
* Historical system metrics
* Process-level troubleshooting
* Diagnosing blocked or hanging applications

[Learn Advanced Diagnostics →](./12-advanced-diagnostics/README.md)

---

### 13. Advanced Storage Management

Go deeper into Linux storage administration.

* LVM
* Physical volumes
* Volume groups
* Logical volumes
* Extending logical volumes
* Filesystem resizing
* Online storage expansion
* NFS
* SMB
* Network-mounted filesystems
* Shared storage
* Storage troubleshooting

[Learn Advanced Storage →](./13-advanced-storage/README.md)

---

### 14. Linux Security & Access Control

Understand how Linux controls what users and applications are allowed to do.

* SELinux
* AppArmor
* Mandatory Access Control (MAC)
* Security contexts
* Security policies
* Permission denials
* PAM
* Authentication
* Authorization
* `iptables`
* `nftables`
* Linux firewall concepts
* Container security basics

[Learn Linux Security →](./14-security/README.md)

---

### 15. Kernel Tuning & Modern Observability

Learn how Linux can be configured and observed at the kernel level.

* `sysctl`
* `/etc/sysctl.conf`
* Kernel parameters
* `vm.swappiness`
* File descriptor limits
* `fs.file-max`
* TCP buffer configuration
* Kernel performance tuning
* eBPF
* Kernel-level observability
* eBPF-based networking and security
* Relationship between eBPF and Kubernetes

[Learn Kernel Tuning & Observability →](./15-kernel-and-observability/README.md)

---

### 16. Logging, Rotation & Auditing

Go beyond basic `journalctl` usage and understand production logging.

* `journalctl`
* `logrotate`
* Log rotation policies
* Compression
* Log retention
* Log file management
* Preventing disk exhaustion
* `auditd`
* Linux auditing
* Tracking command execution
* Tracking file access
* Security auditing

[Learn Logging & Auditing →](./16-logging-and-auditing/README.md)

---

## Practical Skills

Throughout the learning process, focus on practical tasks such as:

* Setting up a Linux server.
* Creating and managing users.
* Configuring permissions.
* Running and troubleshooting services.
* Finding and analyzing logs.
* Monitoring CPU and memory usage.
* Troubleshooting high CPU/memory usage.
* Troubleshooting disk-space issues.
* Troubleshooting inode exhaustion.
* Troubleshooting disk I/O bottlenecks.
* Troubleshooting network connectivity.
* Tracing system calls using `strace`.
* Monitoring historical system performance using `sar`.
* Managing LVM storage.
* Mounting and troubleshooting NFS storage.
* Configuring Linux security policies.
* Tuning kernel parameters.
* Automating repetitive tasks with Bash.
* Connecting to remote servers using SSH.
* Deploying and managing applications.
* Troubleshooting container-related Linux issues.

---

## Production Incident Scenarios

Every topic should contain at least **one realistic production incident scenario**.

The objective is to connect Linux theory with problems encountered in real production systems.

Each topic README should contain a section similar to:

```markdown
## Production Incident Scenario

### Problem

Describe the production issue.

### Symptoms

What did the engineers observe?

### Investigation

Which Linux commands and tools were used?

### Root Cause

What actually caused the issue?

### Resolution

How was the problem fixed?

### Prevention

How could the issue be detected or prevented in the future?
```

Example:

### Disk Space vs Inode Exhaustion

A server reports:

```text
No space left on device
```

But:

```bash
df -h
```

shows that 50% of the disk is still available.

Further investigation:

```bash
df -i
```

shows that the filesystem has exhausted its available inodes.

The investigation should then identify which directories contain a very large number of files and determine why they were created.

This teaches the difference between:

```text
Disk capacity
    ↓
df -h

vs.

Filesystem inode capacity
    ↓
df -i
```

The goal is to develop the ability to move from:

> **"The server is broken."**

to:

> **"I can systematically investigate the symptoms, identify the root cause, fix the problem, and prevent it from happening again."**

---

## Repository Structure

Since this entire section is located inside the main repository's `01-linux/` directory, avoid unnecessary directory nesting.

A recommended structure is:

```text
01-linux/
├── README.md
│
├── 01-linux-fundamentals/
│   └── README.md
│
├── 02-essential-commands/
│   └── README.md
│
├── 03-files-and-permissions/
│   └── README.md
│
├── 04-processes/
│   └── README.md
│
├── 05-shell-and-bash/
│   └── README.md
│
├── 06-package-management/
│   └── README.md
│
├── 07-networking/
│   └── README.md
│
├── 08-storage/
│   └── README.md
│
├── 09-system-management/
│   └── README.md
│
├── 10-linux-internals/
│   └── README.md
│
├── 11-linux-for-devops/
│   └── README.md
│
├── 12-advanced-diagnostics/
│   └── README.md
│
├── 13-advanced-storage/
│   └── README.md
│
├── 14-security/
│   └── README.md
│
├── 15-kernel-and-observability/
│   └── README.md
│
└── 16-logging-and-auditing/
    └── README.md
```

Use additional directories such as `labs/` and `scripts/` only where they provide value.

For example:

```text
02-essential-commands/
├── README.md
└── scripts/

05-shell-and-bash/
├── README.md
└── scripts/

08-storage/
├── README.md
└── labs/

11-linux-for-devops/
├── README.md
├── labs/
└── scripts/
```

The objective is to keep the repository **simple, readable, and easy to maintain**.

---

## Important Commands to Master

The goal is not to memorize every Linux command, but to become comfortable with the commands below.

```text
File Management
---------------
pwd
ls
cd
cp
mv
rm
mkdir
touch
find

File / Text
-----------
cat
less
head
tail
grep
sed
awk
cut
sort
uniq
wc
xargs

Permissions
-----------
chmod
chown
chgrp
umask

Processes
---------
ps
top
htop
kill
pkill
jobs
bg
fg
nice
renice

Networking
----------
ip
ss
ping
curl
wget
dig
ssh
scp
traceroute

Storage
-------
df
du
lsblk
mount
umount

System
------
systemctl
journalctl
uname
hostname
uptime
free
vmstat

Diagnostics
-----------
strace
iostat
sar

Security
--------
iptables
nft
getenforce
sestatus

Storage Administration
----------------------
pvcreate
vgcreate
lvcreate
lvextend

Kernel
------
sysctl

Logging
-------
logrotate
auditctl
ausearch

Automation
----------
cron
crontab
bash
```

---

## Learning Approach

For every topic, follow this pattern:

```text
Concept
   ↓
Understand why it exists
   ↓
Learn the command/tool
   ↓
Practice on Linux
   ↓
Understand what happens internally
   ↓
Troubleshoot a real problem
   ↓
Document the learning
```

For advanced topics:

```text
Concept
   ↓
Understand the kernel/system behavior
   ↓
Learn the tool
   ↓
Reproduce the problem
   ↓
Investigate the problem
   ↓
Identify the root cause
   ↓
Fix the problem
   ↓
Document prevention
```

The objective is to move from:

> **"I know this command."**

to:

> **"I understand why this command is needed, what it does internally, and how to troubleshoot it when it fails."**

---

## Recommended Progression

```text
                    CORE LINUX
                        │
                        ▼
              Linux Fundamentals
                        ↓
              Essential Commands
                        ↓
              Files & Permissions
                        ↓
               Processes & Jobs
                        ↓
                 Shell & Bash
                        ↓
              Package Management
                        ↓
                  Networking
                        ↓
              Storage & Filesystems
                        ↓
             System Management
                        ↓
                Linux Internals
                        ↓
               Linux for DevOps
                        │
                        ▼
              PRODUCTION LINUX
                        │
          ┌─────────────┼─────────────┐
          ↓             ↓             ↓
   Diagnostics      Advanced      Security
    & Tracing       Storage       & Access
          │             │             │
          └─────────────┼─────────────┘
                        ↓
             Kernel & Observability
                        ↓
               Logging & Auditing
```

The **core topics should be completed first**. Advanced topics can then be studied progressively based on production and DevOps requirements.

---

## Completion Checklist

### Core Linux

* [ ] Linux fundamentals
* [ ] Linux filesystem
* [ ] Essential commands
* [ ] File management
* [ ] Users and groups
* [ ] Permissions
* [ ] Processes
* [ ] Job control
* [ ] Bash
* [ ] Package management
* [ ] Networking
* [ ] SSH
* [ ] Storage and filesystems
* [ ] `systemd`
* [ ] Logs
* [ ] Monitoring
* [ ] Linux internals
* [ ] Linux troubleshooting
* [ ] Linux for DevOps
* [ ] Containers and Linux fundamentals
* [ ] Practical Linux projects

### Advanced & Production Linux

* [ ] Advanced diagnostics
* [ ] `strace`
* [ ] `iostat`
* [ ] `sar`
* [ ] Advanced storage
* [ ] LVM
* [ ] NFS
* [ ] SMB
* [ ] SELinux
* [ ] AppArmor
* [ ] PAM
* [ ] `iptables`
* [ ] `nftables`
* [ ] Linux firewall fundamentals
* [ ] `sysctl`
* [ ] Kernel tuning
* [ ] File descriptor limits
* [ ] TCP/kernel tuning
* [ ] eBPF fundamentals
* [ ] `logrotate`
* [ ] `auditd`
* [ ] Linux auditing
* [ ] Production incident scenarios
* [ ] Advanced Linux troubleshooting
