# Linux

Linux is one of the fundamental technologies for DevOps, cloud computing, containers, system administration, and backend engineering.

The goal of this section is to develop a strong understanding of Linux from the fundamentals to advanced system concepts, with a particular focus on **practical usage, troubleshooting, and DevOps**.

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
* Understand the Linux concepts required for DevOps, containers, and cloud environments.

---

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

```text
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

```text
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

```text
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
* Troubleshooting network connectivity.
* Automating repetitive tasks with Bash.
* Connecting to remote servers using SSH.
* Deploying and managing applications.

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

The objective is to move from:

> **"I know this command."**

to:

> **"I understand why this command is needed, what it does internally, and how to troubleshoot it when it fails."**

---

## Recommended Progression

```text
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
```

---

## Completion Checklist

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
