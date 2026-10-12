<div align="center">

<!-- Self-Hosted Native SVG Banner (Guaranteed 100% uptime, zero external renderers) -->
<img src="https://raw.githubusercontent.com/Ujjwal-Devloper-5/Ujjwal-Devloper-5/main/assets/banner.svg" width="100%" alt="Ujjwal Kumar Banner" />

<br/><br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Ujjwal_Kumar-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ujjwalkumar-7b3871256)
[![Email](https://img.shields.io/badge/Email-Get_in_Touch-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:ujjwalkumarbgpg6@gmail.com)
[![Location](https://img.shields.io/badge/Location-Jaipur,_India-10b981?style=for-the-badge&logo=google-maps&logoColor=white)](#)
[![Status](https://img.shields.io/badge/Open_To-Global_Remote_(US/EU/APAC)-6366f1?style=for-the-badge)](#)

<br/>

> **"Build systems that scale. Document decisions that matter. Ship code that works."**

<p align="center">
  <b>Platform Engineer specializing in Distributed Systems, Real-Time Edge AI, and Zero-Trust Cloud Infrastructure.</b><br/>
  Experienced in building event-driven microservices, high-throughput Kafka streaming pipelines, GPU-accelerated vision engines, and declarative GitOps delivery.
</p>

</div>

---

## 🏛️ The Engineering Quadrant

<div align="center">

```
         ┌─────────────────────────────────────────────────────────────┐
         │                        UJJWAL KUMAR                         │
         │               AI Systems & Platform Engineer                │
         └──────────────────────────────┬──────────────────────────────┘
                                       │
         ┌────────────────────┬─────────┴─────────┬────────────────────┐
         ▼                    ▼                   ▼                    ▼
  [ SECUREDROP ]          [ ARGUS ]         [ OMNIAGENT ]      [ SYSTEMBACKUP ]
 Distributed Cloud    Edge Computer Vision   Agent Swarms       Linux Kernel & 
  & GitOps Engine    & Kafka Stream Engine   & MCP Runtime     Disaster Recovery
```

</div>

---

## 🚀 Featured Production Systems

### 1. 👁️ [Argus — Edge AI & Real-Time Security Sentinel](https://github.com/Ujjwal-Devloper-5/argus)
> **A self-hosted, privacy-first computer vision sentinel transforming RTSP IP cameras into thinking security nodes.**

[![Python](https://img.shields.io/badge/Python-3.11+-3776AB?style=flat-square&logo=python&logoColor=white)](https://python.org)
[![CUDA](https://img.shields.io/badge/CUDA-NVIDIA_NVENC-76B900?style=flat-square&logo=nvidia&logoColor=white)](https://developer.nvidia.com/cuda-zone)
[![Kafka](https://img.shields.io/badge/Apache_Kafka-KRaft_Mode-231F20?style=flat-square&logo=apachekafka&logoColor=white)](https://kafka.apache.org)
[![Tests](https://img.shields.io/badge/Pytest-661_Passing_(78%25_Coverage)-22c55e?style=flat-square&logo=pytest&logoColor=white)](#)

* **Dual-Brain Cognitive Architecture:** System 1 on-device 421M gate model ([`convaiinnovations/laya-typed-decisions`](https://huggingface.co/convaiinnovations/laya-typed-decisions)) evaluates urgency in milliseconds; System 2 Vision LLM (LLaVA/Ollama/Claude/GPT-4o) executes deep scene analysis *only* on confirmed anomalies.
* **GPU-Accelerated Vision Pipeline:** MOG2 background subtractor drops ~90% of static frames before GPU ingestion; YOLOv8 person detection + InsightFace ArcFace (512-dim embeddings with sub-millisecond FAISS vector search); Kalman-filter SORT tracking.
* **Resilient Event Streaming:** Decoupled over 4 Kafka topics with 3-retry exponential backoff, dead letter queue (DLQ), and manual offset commits guaranteeing zero event loss on crash. Zero-copy circular buffer recording via FFmpeg NVENC hardware encoding.
* **AutoLearner & Alerts:** Laplacian sharpness scoring of crops, temporal anomaly detection (3 AM repeat visitors), and two-way interactive enrollment via Telegram and Discord.

---

### 2. 🛡️ [SystemBackup — AI-Driven Linux Disaster Recovery Suite](https://github.com/Ujjwal-Devloper-5/SystemBackup)
> **Intelligent, zero-trust disaster recovery and backup orchestrator officially distributed on the Arch User Repository (AUR).**

[![AUR](https://img.shields.io/aur/version/sysbackup-git?color=1793d1&style=flat-square&logo=archlinux&logoColor=white)](https://aur.archlinux.org/packages/sysbackup-git)
[![Engine](https://img.shields.io/badge/Engine-Restic_%2B_Rclone-0052cc?style=flat-square)](#)
[![Security](https://img.shields.io/badge/Encryption-Native_AES--256-green?style=flat-square)](#)

* **Real-Time Z-Score Anomaly Detection:** Mathematical heuristic engine detects ransomware encryption spikes or accidental mass deletions on snapshot deltas, immediately halting cloud replication to protect recovery vaults.
* **Predictive Storage Analytics:** Linear regression forecasting models predict days remaining until local or cloud storage exhaustion.
* **Kernel & Resource Isolation:** Managed via systemd timers bound to strict Linux cgroups (`CPUQuota=50%`, `Nice=19`, `ionice -c 3`); monitors load average and `xprintidle` to defer backups until the workstation is idle.
* **Multi-Cloud Disaster Recovery:** Deduplicated AES-256 snapshots synchronized across AWS S3, Google Drive, and Backblaze B2, managed via an interactive TUI wizard (`gum`).

---

### 3. 🐝 [OmniAgent — Multi-Platform Swarm AI Engine](https://github.com/Ujjwal-Devloper-5/OmniAgent)
> **Production-grade self-hosted agent platform running across Discord, Telegram, and Slack with LangGraph swarms.**

[![Python](https://img.shields.io/badge/Python-3.12+-3776AB?style=flat-square&logo=python&logoColor=white)](https://python.org)
[![LangGraph](https://img.shields.io/badge/Orchestrator-LangGraph_Swarm-FF6B6B?style=flat-square)](#)
[![MCP](https://img.shields.io/badge/Protocol-Model_Context_Protocol_(MCP)-00D084?style=flat-square)](#)
[![Docker](https://img.shields.io/badge/Sandbox-Ubuntu_24.04_Container-2496ED?style=flat-square&logo=docker&logoColor=white)](#)

* **Autonomous Agent Swarm:** Supervisor pattern coordinates `ResearchAgent` (live data gathering) → `AnalystAgent` (insight extraction) → `WriterAgent` (document generation), bounded by strict step limits (`MAX_STEPS=5`, `TIMEOUT=90s`).
* **Dynamic Scored Model Registry:** Real-time scoring by `intelligence`, `speed`, and `tool_reliability`; automatically degrades scores on consecutive failures and routes to next-best models without service restarts.
* **Self-Healing Memory:** Detects corrupted checkpoints from crashed MCP tools, automatically purges dirty state, and retries transactions seamlessly.
* **Isolated Execution Sandbox:** Ephemeral Ubuntu 24.04 Docker containers execute untrusted Python code with persistent workspace isolation. Live dark-mode Web Admin Dashboard (port 8181) and automated styled PDF delivery to chat.

---

### 4. 🚀 [SecureDrop — Distributed Microservices Platform](https://github.com/Ujjwal-Devloper-5/secure-drop-backend)
> **High-throughput 11-microservice distributed authentication and data platform built with GitOps automation.**

[![Go](https://img.shields.io/badge/Go-1.22+-00ADD8?style=flat-square&logo=go&logoColor=white)](https://golang.org)
[![Node.js](https://img.shields.io/badge/Node.js-20+-339933?style=flat-square&logo=node.js&logoColor=white)](https://nodejs.org)
[![Kubernetes](https://img.shields.io/badge/Kubernetes-K3s_Cluster-326CE5?style=flat-square&logo=kubernetes&logoColor=white)](https://kubernetes.io)
[![ArgoCD](https://img.shields.io/badge/GitOps-ArgoCD_App--of--Apps-EF7B4D?style=flat-square&logo=argo&logoColor=white)](https://argoproj.github.io/cd/)

* **Microservices Ecosystem:** 11 decoupled domain services running on K3s with clear RPC/event boundaries and polyglot persistence (MySQL, MongoDB, Redis).
* **Kafka Event Bus:** Asynchronous event streaming with dedicated consumer groups, dead letter queues (DLQs), and automated retry policies.
* **ArgoCD App-of-Apps GitOps:** Declarative multi-app deployment lifecycle; synchronizes entire application sets from Git manifests without manual `kubectl` intervention.
* **Production Quality Gates:** Multi-stage GitHub Actions CI/CD pipelines with 73+ automated tests (85%+ coverage), k6 load testing, and webhook telemetry (Discord/Slack).
* **Deep RCA Documentation:** Includes production root-cause analysis: [Kafka Production Issues Analysis](https://github.com/Ujjwal-Devloper-5/secure-drop-backend/blob/master/KAFKA_ISSUES_ANALYSIS.md).

---

## 🖥️ Infrastructure & Systems Engineering

* **Bare-Metal Linux Operations:** Daily-driver Arch Linux environment with LUKS-encrypted root storage; deep kernel diagnostics (`/proc` thread stack inspection, cgroups, systemd drop-ins, Wayland/EGL hardware acceleration).
* **Hypervisor & Virtualization Fleet:** Headless KVM/QEMU virtual machines managed via `libvirt` with VirtIO drivers and PCIe hardware passthrough.
* **Dual-Layer Mesh Networking:** Isolated internal VirtIO network bridges combined with an encrypted Tailscale overlay mesh; host-level filtering via OpenSnitch eBPF and CrowdSec intrusion prevention.
* **Infrastructure as Code (IaC):** Automated multi-VM configuration management using **Ansible** and cloud provisioning via **Terraform** on AWS.

---

## 🛠️ Technical Stack & Tooling

| Domain | Technologies & Frameworks |
| :--- | :--- |
| **Languages** | Python, Go (Golang), TypeScript, JavaScript, Bash / Shell, SQL |
| **Distributed Systems** | Apache Kafka (KRaft), Event-Driven Architecture, Microservices, Dead Letter Queues (DLQ), Redis |
| **Cloud & Orchestration** | Kubernetes (K3s), Docker, Terraform (AWS), Ansible, ArgoCD (GitOps App-of-Apps) |
| **Databases & Storage** | PostgreSQL, MySQL, MongoDB, Redis, Restic, Rclone, Polyglot Persistence |
| **AI & Computer Vision** | LangGraph, Model Context Protocol (MCP), YOLOv8, InsightFace (ArcFace), FAISS, Ollama, LLaVA |
| **Linux & Systems** | Arch Linux, KVM / QEMU, Libvirt, Systemd Cgroups, EGL/Wayland, OpenSnitch eBPF, UFW |
| **CI/CD & Observability** | GitHub Actions, Prometheus, Grafana, Jest, Pytest, k6 Load Testing, Winston Logging |

---

## 📊 Live Metrics & GitHub Telemetry

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=Ujjwal-Devloper-5&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0D1117&include_all_commits=true&count_private=true" alt="Ujjwal's GitHub Stats" height="165" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Ujjwal-Devloper-5&layout=compact&theme=tokyonight&hide_border=true&bg_color=0D1117&langs_count=8" alt="Top Languages" height="165" />

<br/>

[![GitHub Streak](https://streak-stats.demolab.com/?user=Ujjwal-Devloper-5&theme=tokyonight&hide_border=true&background=0D1117)](https://git.io/streak-stats)

</div>

---

## 🤝 Let's Connect

I am actively open to **Platform Engineering**, **Distributed Systems**, **Cloud Infrastructure**, and **SRE** opportunities (Full-time or High-impact Contract — US/EU/APAC remote hours available).

* 📧 **Email:** [ujjwalkumarbgpg6@gmail.com](mailto:ujjwalkumarbgpg6@gmail.com)
* 💼 **LinkedIn:** [linkedin.com/in/ujjwalkumar-7b3871256](https://www.linkedin.com/in/ujjwalkumar-7b3871256)
* 🌐 **Location:** Jaipur, India (Remote Available)

<div align="center">
  <sub>Designed & engineered with precision by Ujjwal Kumar.</sub>
</div>
