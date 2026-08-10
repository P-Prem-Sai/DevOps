# 🚀 DevOps / Platform Engineering Roadmap

A structured roadmap to build **in-depth knowledge of Linux, Networking, Containers, Kubernetes, Cloud, Infrastructure as Code, CI/CD, GitOps, Observability, and System Design**.

The goal is to move from **using individual tools** to understanding how they work internally, how they fit together, and how to design and troubleshoot production systems.

---

# 🗺️ Learning Path

```text
Linux
  ↓
Networking
  ↓
Docker
  ↓
Python + Bash Scripting
  ↓
Kubernetes
  ↓
Terraform
  ↓
AWS
  ↓
EKS
  ↓
GitHub Actions
  ↓
GitOps (ArgoCD)
  ↓
Prometheus + Grafana
  ↓
System Design
```

---

# 📚 1. Linux

## Goal

Build a strong understanding of Linux internals, processes, memory, filesystems, networking, troubleshooting, and system administration.

### Fundamentals

* [ ] Linux filesystem
* [ ] File permissions
* [ ] Users and groups
* [ ] Environment variables
* [ ] Package management
* [ ] Processes
* [ ] Threads
* [ ] Process states
* [ ] Signals
* [ ] Daemons
* [ ] systemd
* [ ] Cron
* [ ] SSH

### CPU & Memory

* [ ] CPU architecture basics
* [ ] CPU scheduling
* [ ] Context switching
* [ ] Load average
* [ ] Virtual memory
* [ ] Physical memory
* [ ] Pages
* [ ] Page tables
* [ ] Swap
* [ ] OOM Killer

### Filesystems & I/O

* [ ] Filesystems
* [ ] Inodes
* [ ] Hard links
* [ ] Soft links
* [ ] Mounts
* [ ] Disk usage
* [ ] `/proc`
* [ ] `/sys`
* [ ] stdin
* [ ] stdout
* [ ] stderr
* [ ] Pipes
* [ ] Redirection

### Important Commands

```bash
ls
find
grep
awk
sed
cut
sort
uniq
xargs

ps
top
htop
kill
free
vmstat

df
du
mount

systemctl
journalctl

ip
ss
curl
dig
tcpdump
```

### Troubleshooting

* [ ] High CPU usage
* [ ] High memory usage
* [ ] OOM
* [ ] Full disk
* [ ] Process not responding
* [ ] Service not starting
* [ ] Port not accessible
* [ ] Zombie processes
* [ ] File permission issues

---

# 🌐 2. Networking

## Goal

Build a strong understanding of networking before moving into Docker and Kubernetes networking.

### Network Fundamentals

* [ ] OSI Model
* [ ] TCP/IP Model
* [ ] MAC Address
* [ ] IP Address
* [ ] IPv4
* [ ] IPv6 basics
* [ ] Ports
* [ ] Sockets
* [ ] Client / Server model

### TCP / UDP

* [ ] TCP
* [ ] UDP
* [ ] TCP 3-way handshake
* [ ] Connection termination
* [ ] TCP retransmission
* [ ] Flow control
* [ ] Congestion control
* [ ] TCP vs UDP

### IP & Routing

* [ ] Subnetting
* [ ] CIDR
* [ ] Private IP
* [ ] Public IP
* [ ] Default Gateway
* [ ] Routing
* [ ] Routing tables
* [ ] NAT
* [ ] PAT

### DNS

* [ ] DNS
* [ ] DNS hierarchy
* [ ] Root servers
* [ ] TLD servers
* [ ] Authoritative DNS
* [ ] Recursive DNS
* [ ] A record
* [ ] AAAA record
* [ ] CNAME
* [ ] TXT
* [ ] TTL
* [ ] DNS caching
* [ ] DNS resolution path

### HTTP / HTTPS

* [ ] HTTP
* [ ] HTTP methods
* [ ] HTTP headers
* [ ] HTTP status codes
* [ ] Cookies
* [ ] Sessions
* [ ] HTTP/1.1
* [ ] HTTP/2 basics
* [ ] HTTPS
* [ ] TLS
* [ ] TLS handshake
* [ ] Certificates
* [ ] Certificate Authorities
* [ ] TLS termination

### Network Components

* [ ] Switch
* [ ] Router
* [ ] Firewall
* [ ] Proxy
* [ ] Reverse Proxy
* [ ] Load Balancer
* [ ] CDN

### Troubleshooting

* [ ] `ping`
* [ ] `traceroute`
* [ ] `curl`
* [ ] `dig`
* [ ] `nslookup`
* [ ] `ss`
* [ ] `nc`
* [ ] `tcpdump`

### Troubleshooting Scenarios

* [ ] DNS resolution failure
* [ ] Connection timeout
* [ ] Connection refused
* [ ] Port blocked
* [ ] Routing failure
* [ ] TLS certificate failure
* [ ] Application reachable locally but not remotely

---

# 🐳 3. Docker

## Goal

Understand containers from both the practical and internal Linux perspective.

### Fundamentals

* [ ] Containers vs VMs
* [ ] Docker architecture
* [ ] Docker Engine
* [ ] Docker CLI
* [ ] Images
* [ ] Containers
* [ ] Dockerfile
* [ ] Image layers
* [ ] Registry
* [ ] Docker Hub
* [ ] ECR

### Docker Internals

* [ ] Linux namespaces
* [ ] PID namespace
* [ ] Network namespace
* [ ] Mount namespace
* [ ] User namespace
* [ ] cgroups
* [ ] Container runtime
* [ ] containerd
* [ ] runc
* [ ] OCI

### Networking

* [ ] Bridge network
* [ ] Host network
* [ ] Container network
* [ ] Port mapping
* [ ] Container DNS

### Storage

* [ ] Volumes
* [ ] Bind mounts
* [ ] tmpfs
* [ ] Overlay filesystem

### Docker Security

* [ ] Root vs non-root
* [ ] Linux capabilities
* [ ] Read-only filesystem
* [ ] Secrets
* [ ] Image scanning
* [ ] Minimal images

### Docker Compose

* [ ] Docker Compose
* [ ] Multi-container applications
* [ ] Service dependencies
* [ ] Networks
* [ ] Volumes
* [ ] Environment configuration

### Practice

* [ ] Containerize Flask application
* [ ] Create multi-container application
* [ ] Configure networking
* [ ] Configure persistent storage
* [ ] Add health checks
* [ ] Optimize Dockerfile
* [ ] Run containers as non-root
* [ ] Debug container failures

---

# 🐍 4. Python + Bash Scripting

## Goal

Build practical automation skills for DevOps, Cloud, CI/CD, Kubernetes, and infrastructure troubleshooting.

---

## Bash

### Fundamentals

* [ ] Variables
* [ ] Conditions
* [ ] Loops
* [ ] Functions
* [ ] Arguments
* [ ] Exit codes
* [ ] Environment variables
* [ ] Command substitution
* [ ] Pipes
* [ ] Redirection

### Commands

```bash
grep
awk
sed
cut
sort
uniq
xargs
find
jq
curl
wget
ps
top
df
du
ss
ip
systemctl
journalctl
```

### Automation

* [ ] Service health checks
* [ ] Process monitoring
* [ ] Log parsing
* [ ] File management
* [ ] Deployment scripts
* [ ] Backup scripts
* [ ] System monitoring scripts

---

## Python

### Fundamentals

* [ ] Variables
* [ ] Lists
* [ ] Dictionaries
* [ ] Sets
* [ ] Tuples
* [ ] Functions
* [ ] Classes
* [ ] Exceptions
* [ ] File handling
* [ ] JSON
* [ ] YAML

### DevOps Python

* [ ] `os`
* [ ] `sys`
* [ ] `subprocess`
* [ ] `pathlib`
* [ ] `json`
* [ ] `requests`
* [ ] Logging
* [ ] REST APIs

### AWS Automation

* [ ] boto3
* [ ] EC2 automation
* [ ] S3 automation
* [ ] IAM automation
* [ ] CloudWatch automation

### Kubernetes Automation

* [ ] Kubernetes Python client
* [ ] API interaction
* [ ] Resource monitoring
* [ ] Automation scripts

### Practice

* [ ] Log analyzer
* [ ] Server health checker
* [ ] API automation
* [ ] AWS resource inventory script
* [ ] Kubernetes resource checker
* [ ] Deployment automation script

---

# ☸️ 5. Kubernetes

## Goal

Understand Kubernetes architecture, orchestration, networking, storage, scheduling, security, scaling, and troubleshooting.

### Architecture

* [ ] Control Plane
* [ ] API Server
* [ ] etcd
* [ ] Scheduler
* [ ] Controller Manager
* [ ] Worker Node
* [ ] kubelet
* [ ] kube-proxy
* [ ] Container Runtime

### Core Objects

* [ ] Pod
* [ ] ReplicaSet
* [ ] Deployment
* [ ] Service
* [ ] Namespace
* [ ] ConfigMap
* [ ] Secret
* [ ] DaemonSet
* [ ] StatefulSet
* [ ] Job
* [ ] CronJob

### Networking

* [ ] Pod networking
* [ ] CNI
* [ ] Service networking
* [ ] ClusterIP
* [ ] NodePort
* [ ] LoadBalancer
* [ ] CoreDNS
* [ ] Ingress
* [ ] NetworkPolicy

### Storage

* [ ] Volume
* [ ] PV
* [ ] PVC
* [ ] StorageClass

### Scheduling & Scaling

* [ ] Requests
* [ ] Limits
* [ ] QoS
* [ ] HPA
* [ ] Affinity
* [ ] Anti-affinity
* [ ] Taints
* [ ] Tolerations

### Security

* [ ] RBAC
* [ ] Role
* [ ] RoleBinding
* [ ] ServiceAccount
* [ ] Pod Security
* [ ] Secrets

### Troubleshooting

* [ ] CrashLoopBackOff
* [ ] ImagePullBackOff
* [ ] Pending Pods
* [ ] OOMKilled
* [ ] Readiness failures
* [ ] Liveness failures
* [ ] DNS failures
* [ ] Network failures

### Important Commands

```bash
kubectl get
kubectl describe
kubectl logs
kubectl exec
kubectl apply
kubectl delete
kubectl rollout
kubectl scale
kubectl top
kubectl get events
```

---

# 🏗️ 6. Terraform

## Goal

Learn Infrastructure as Code and provision infrastructure reproducibly instead of manually creating infrastructure through the AWS Console.

### Fundamentals

* [ ] Infrastructure as Code
* [ ] Terraform architecture
* [ ] Providers
* [ ] Resources
* [ ] Variables
* [ ] Outputs
* [ ] Locals
* [ ] Data Sources
* [ ] Dependencies

### Terraform State

* [ ] State
* [ ] State locking
* [ ] Remote state
* [ ] Backend
* [ ] State drift
* [ ] Import

### Modules

* [ ] Module structure
* [ ] Reusable modules
* [ ] Module inputs
* [ ] Module outputs
* [ ] Module composition

### Commands

```bash
terraform init
terraform validate
terraform fmt
terraform plan
terraform apply
terraform destroy
terraform state
terraform import
```

### Practice

Provision using Terraform:

```text
VPC
 ↓
Subnets
 ↓
Route Tables
 ↓
Security Groups
 ↓
IAM
 ↓
EC2
 ↓
S3
```

Later:

```text
Terraform
    ↓
EKS
```

---

# ☁️ 7. AWS

## Goal

Understand AWS infrastructure deeply enough to design, provision, secure, monitor, and troubleshoot production systems.

### AWS Fundamentals

* [ ] Regions
* [ ] Availability Zones
* [ ] AWS Global Infrastructure
* [ ] Shared Responsibility Model

### IAM

* [ ] Users
* [ ] Groups
* [ ] Roles
* [ ] Policies
* [ ] Trust Policies
* [ ] STS
* [ ] AssumeRole
* [ ] Least Privilege

### VPC

* [ ] VPC
* [ ] CIDR
* [ ] Public Subnet
* [ ] Private Subnet
* [ ] Route Table
* [ ] Internet Gateway
* [ ] NAT Gateway
* [ ] Security Group
* [ ] NACL
* [ ] VPC Endpoints

### Compute

* [ ] EC2
* [ ] AMI
* [ ] Instance Types
* [ ] EBS
* [ ] Auto Scaling

### Networking

* [ ] ALB
* [ ] Target Groups
* [ ] Health Checks
* [ ] Route 53
* [ ] DNS

### Storage

* [ ] S3
* [ ] Versioning
* [ ] Lifecycle
* [ ] Encryption
* [ ] Multipart Upload
* [ ] Presigned URLs

### Monitoring

* [ ] CloudWatch Metrics
* [ ] CloudWatch Logs
* [ ] CloudWatch Alarms

### Containers

* [ ] ECR
* [ ] EKS

---

# ☸️ 8. EKS

## Goal

Understand how Kubernetes integrates with AWS networking, IAM, load balancing, storage, and security.

### Architecture

* [ ] EKS Control Plane
* [ ] Managed Node Groups
* [ ] Worker Nodes
* [ ] EKS Add-ons

### Networking

* [ ] VPC CNI
* [ ] Pod IP allocation
* [ ] AWS Load Balancer Controller
* [ ] ALB
* [ ] NLB
* [ ] Service networking

### IAM Integration

* [ ] OIDC
* [ ] IRSA
* [ ] IAM Roles for Pods
* [ ] Least privilege

### AWS Integration

* [ ] ECR
* [ ] EBS CSI
* [ ] Load Balancers
* [ ] CloudWatch

### Security

* [ ] EKS RBAC
* [ ] IAM
* [ ] NetworkPolicy
* [ ] Secrets

### Troubleshooting

* [ ] Pod scheduling
* [ ] Networking failures
* [ ] IAM failures
* [ ] Image pull failures
* [ ] Load Balancer failures
* [ ] Node failures
* [ ] DNS failures

---

# ⚙️ 9. GitHub Actions

## Goal

Build secure and production-grade CI pipelines and understand how CI integrates with GitOps-based CD.

### Fundamentals

* [ ] Workflows
* [ ] Events
* [ ] Jobs
* [ ] Steps
* [ ] Runners
* [ ] Expressions

### Advanced

* [ ] Self-hosted runners
* [ ] Matrix builds
* [ ] Artifacts
* [ ] Caching
* [ ] Environments
* [ ] Secrets
* [ ] Variables
* [ ] Reusable Workflows
* [ ] Composite Actions
* [ ] Concurrency

### Security

* [ ] OIDC
* [ ] AWS authentication
* [ ] Least privilege
* [ ] Secret management
* [ ] Dependency security
* [ ] Container scanning

### CI Pipeline

```text
Pull Request
      ↓
Lint
      ↓
Unit Tests
      ↓
Build
      ↓
Security Scan
      ↓
Docker Build
      ↓
Push Image → ECR
```

---

# 🔄 10. GitOps — ArgoCD

## Goal

Understand modern Kubernetes Continuous Delivery using a **pull-based GitOps model**.

### GitOps Fundamentals

* [ ] What is GitOps?
* [ ] Push vs Pull deployment
* [ ] Desired State
* [ ] Declarative Configuration
* [ ] Git as Source of Truth
* [ ] Drift Detection
* [ ] Reconciliation

### ArgoCD

* [ ] ArgoCD architecture
* [ ] Application
* [ ] ApplicationSet
* [ ] Repository
* [ ] Project
* [ ] Sync
* [ ] Auto Sync
* [ ] Manual Sync
* [ ] Health Status
* [ ] Sync Status
* [ ] Drift Detection
* [ ] Rollback

### GitOps Pipeline

```text
Developer
    ↓
Git Repository
    ↓
GitHub Actions
    ↓
Build + Test
    ↓
Docker Image
    ↓
ECR
    ↓
Update Kubernetes Manifest
    ↓
GitOps Repository
    ↓
ArgoCD
    ↓
Kubernetes / EKS
```

### Practice

* [ ] Deploy ArgoCD
* [ ] Connect Git repository
* [ ] Deploy application using ArgoCD
* [ ] Enable automatic sync
* [ ] Introduce configuration drift
* [ ] Observe reconciliation
* [ ] Perform rollback
* [ ] Manage multiple environments

---

# 📊 11. Prometheus + Grafana

## Goal

Build production-level observability for infrastructure and Kubernetes applications.

### Observability

* [ ] Logs
* [ ] Metrics
* [ ] Traces
* [ ] Monitoring
* [ ] Alerting
* [ ] SLI
* [ ] SLO
* [ ] SLA

### Prometheus

* [ ] Prometheus architecture
* [ ] Scraping
* [ ] Exporters
* [ ] Time Series
* [ ] Labels
* [ ] PromQL
* [ ] Service Discovery
* [ ] Alerting

### Grafana

* [ ] Dashboards
* [ ] Data Sources
* [ ] Panels
* [ ] Variables
* [ ] Alerts

### Monitor

```text
CPU
Memory
Disk
Network
Request Rate
Error Rate
Latency
Pod Restarts
Container Health
Kubernetes Resources
```

### Practice

* [ ] Deploy Prometheus
* [ ] Deploy Grafana
* [ ] Monitor Kubernetes
* [ ] Create dashboards
* [ ] Create alerts
* [ ] Monitor application metrics
* [ ] Investigate production-like incidents

---

# 🏛️ 12. System Design

## Goal

Learn to design scalable, reliable, secure, observable, and cost-effective production systems.

### Fundamentals

* [ ] Scalability
* [ ] Availability
* [ ] Reliability
* [ ] Performance
* [ ] Fault Tolerance
* [ ] Security
* [ ] Cost Optimization

### Building Blocks

* [ ] Load Balancer
* [ ] Reverse Proxy
* [ ] API Gateway
* [ ] Cache
* [ ] Database
* [ ] Database Replication
* [ ] Database Sharding
* [ ] Message Queue
* [ ] Pub/Sub
* [ ] CDN
* [ ] Object Storage
* [ ] Rate Limiting

### Distributed Systems

* [ ] CAP Theorem
* [ ] Consistency
* [ ] Replication
* [ ] Partitioning
* [ ] Idempotency
* [ ] Retries
* [ ] Timeouts
* [ ] Circuit Breaker
* [ ] Backpressure
* [ ] Leader Election

### DevOps / Platform System Design

* [ ] CI/CD Platform
* [ ] Container Deployment Platform
* [ ] Kubernetes Platform
* [ ] Log Aggregation System
* [ ] Monitoring Platform
* [ ] Internal Developer Platform
* [ ] Infrastructure Provisioning Platform

---

# 🏗️ Final Project

Build one complete production-like platform that combines everything.

```text
                              GitHub
                                │
                                ▼
                         GitHub Actions
                                │
                   ┌────────────┴────────────┐
                   │                         │
                 Tests                 Security Scan
                   │                         │
                   └────────────┬────────────┘
                                ▼
                             Docker
                                │
                                ▼
                              ECR
                                │
                                ▼
                         GitOps Repository
                                │
                                ▼
                              ArgoCD
                                │
                                ▼
                              EKS
                                │
                    ┌───────────┴───────────┐
                    │                       │
                 Flask API               Worker
                    │                       │
                    └───────────┬───────────┘
                                │
                         ┌──────┴──────┐
                         │             │
                        S3          Database


Infrastructure
      │
      ▼
  Terraform
      │
      ▼
     AWS


Observability

Application / Kubernetes
          │
          ▼
      Prometheus
          │
          ▼
       Grafana

Logs
  │
  ▼
CloudWatch
```

---

# 🧠 Learning Method

For every technology and concept, answer these seven questions:

1. **What is it?**
2. **Why do we need it?**
3. **How does it work?**
4. **What happens internally?**
5. **What can go wrong?**
6. **How do I troubleshoot it?**
7. **How is it used in production?**

The goal is not to memorize commands.

The goal is to understand **why the system works and what happens when it doesn't**.

---

# 💻 Interview Languages

## DSA → Java

Use **Java** for:

* [ ] Arrays
* [ ] Strings
* [ ] HashMap / HashSet
* [ ] Stack / Queue
* [ ] Binary Search
* [ ] Trees
* [ ] Graphs
* [ ] Intervals
* [ ] Dynamic Programming

## Infrastructure Automation → Python

Use **Python** for:

* [ ] AWS automation
* [ ] REST APIs
* [ ] JSON/YAML processing
* [ ] Kubernetes automation
* [ ] Log processing
* [ ] Infrastructure utilities

## Linux / CI/CD → Bash

Use **Bash** for:

* [ ] Linux automation
* [ ] Process management
* [ ] File operations
* [ ] Log processing
* [ ] Deployment scripts
* [ ] CI/CD utilities

### Language Strategy

```text
                Interview Coding
                       │
                     Java
                       │
                      DSA


              Infrastructure
                     / \
                    /   \
                Python   Bash
                  │        │
              Automation  Linux
              AWS         CI/CD
              APIs        Scripts
              K8s         Debugging
```

---

# 🎯 Final Outcome

After completing this roadmap, the target is to be able to:

* [ ] Understand Linux internals
* [ ] Troubleshoot Linux systems
* [ ] Understand networking from packet to application
* [ ] Build and optimize Docker containers
* [ ] Understand container internals
* [ ] Write Bash automation
* [ ] Write Python automation
* [ ] Deploy and troubleshoot Kubernetes applications
* [ ] Provision infrastructure using Terraform
* [ ] Design AWS infrastructure
* [ ] Deploy and manage EKS
* [ ] Build secure GitHub Actions CI pipelines
* [ ] Implement GitOps using ArgoCD
* [ ] Monitor infrastructure using Prometheus and Grafana
* [ ] Troubleshoot production-like failures
* [ ] Design scalable distributed systems
* [ ] Solve DSA problems using Java

---

# 🚀 Target Roles

* **DevOps Engineer**
* **Platform Engineer**
* **Cloud DevOps Engineer**
* **Site Reliability Engineer (SRE)**
* **Infrastructure Engineer**
* **Cloud Engineer**
* **Infrastructure Automation Engineer**
* **Platform / Developer Productivity Engineer**

---

# 📌 Core Principle

```text
Don't just learn the tool.

Understand:

Tool
 ↓
Why?
 ↓
How?
 ↓
Internals
 ↓
Failure Modes
 ↓
Troubleshooting
 ↓
Production Architecture
```

**Learn deeply. Build everything. Break everything. Fix everything.**
