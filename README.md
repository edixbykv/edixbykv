# Kuldeep Vishwakarma

Software Engineer — AI Systems, Computer Vision, Enterprise Desktop Applications

[edixbykv@gmail.com](mailto:edixbykv@gmail.com) · [GitHub](https://github.com/edixbykv)

---

## 01 Tech Stack

| Category | Stack |
|---|---|
| Languages | ![Python](https://img.shields.io/badge/Python-555?style=flat-square&logo=python&logoColor=white) ![C#](https://img.shields.io/badge/C%23-555?style=flat-square&logo=csharp&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-555?style=flat-square&logo=typescript&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-555?style=flat-square&logo=javascript&logoColor=white) ![SQL](https://img.shields.io/badge/SQL-555?style=flat-square) |
| Desktop | ![.NET](https://img.shields.io/badge/.NET-555?style=flat-square&logo=dotnet&logoColor=white) ![WPF](https://img.shields.io/badge/WPF-555?style=flat-square) ![WinUI](https://img.shields.io/badge/WinUI-555?style=flat-square) |
| Backend | ![FastAPI](https://img.shields.io/badge/FastAPI-555?style=flat-square&logo=fastapi&logoColor=white) ![Node.js](https://img.shields.io/badge/Node.js-555?style=flat-square&logo=nodedotjs&logoColor=white) ![Express](https://img.shields.io/badge/Express-555?style=flat-square&logo=express&logoColor=white) |
| Frontend | ![Next.js](https://img.shields.io/badge/Next.js-555?style=flat-square&logo=nextdotjs&logoColor=white) ![React](https://img.shields.io/badge/React-555?style=flat-square&logo=react&logoColor=white) ![Tailwind](https://img.shields.io/badge/Tailwind-555?style=flat-square&logo=tailwindcss&logoColor=white) ![Three.js](https://img.shields.io/badge/Three.js-555?style=flat-square&logo=threedotjs&logoColor=white) |
| Database | ![SQLite](https://img.shields.io/badge/SQLite-555?style=flat-square&logo=sqlite&logoColor=white) ![SQL Server](https://img.shields.io/badge/SQL_Server-555?style=flat-square&logo=microsoftsqlserver&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-555?style=flat-square&logo=postgresql&logoColor=white) |
| AI / ML | ![PyTorch](https://img.shields.io/badge/PyTorch-555?style=flat-square&logo=pytorch&logoColor=white) ![TensorFlow](https://img.shields.io/badge/TensorFlow-555?style=flat-square&logo=tensorflow&logoColor=white) ![OpenCV](https://img.shields.io/badge/OpenCV-555?style=flat-square&logo=opencv&logoColor=white) ![MediaPipe](https://img.shields.io/badge/MediaPipe-555?style=flat-square&logo=mediapipe&logoColor=white) ![YOLO](https://img.shields.io/badge/YOLO-555?style=flat-square) ![CNN](https://img.shields.io/badge/CNN-555?style=flat-square) ![Vision Transformer](https://img.shields.io/badge/Vision_Transformer-555?style=flat-square) ![Scikit-learn](https://img.shields.io/badge/Scikit_learn-555?style=flat-square&logo=scikitlearn&logoColor=white) |
| Tools | ![Git](https://img.shields.io/badge/Git-555?style=flat-square&logo=git&logoColor=white) ![GitHub](https://img.shields.io/badge/GitHub-555?style=flat-square&logo=github&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-555?style=flat-square&logo=docker&logoColor=white) ![VS Code](https://img.shields.io/badge/VS_Code-555?style=flat-square&logo=visualstudiocode&logoColor=white) ![Visual Studio](https://img.shields.io/badge/Visual_Studio-555?style=flat-square&logo=visualstudio&logoColor=white) |

---

## 02 Engineering Expertise

| | |
|---|---|
| Windows Desktop Software | REST APIs |
| Enterprise Software | Performance Optimization |
| AI Applications | Multithreading |
| Computer Vision | Memory Management |
| Machine Learning | Database Design |
| Secure Data Erasure | System Programming |
| Automation | |

---

## 03 Featured Projects

### Data Sanitization Suite

**Overview**
Enterprise-grade secure data erasure application for Windows, built to permanently destroy data on storage drives in compliance with recognized data-destruction standards, with audit-ready reporting.

**Architecture**
Desktop application (WPF, MVVM) with direct disk I/O via Win32 and low-level drive APIs, backed by a local SQLite store for job history, logs, and generated reports.

**Tech Stack**
`C#` `.NET` `WPF` `SQLite` `Win32 API` `Disk APIs`

**Algorithms**
- DoD 5220.22-M
- NIST 800-88
- Random pass overwrite
- Zero-fill
- Cryptographic erase
- Post-wipe verification (SHA-256, CRC)

**Performance Notes**
Sequential, buffered I/O and asynchronous drive operations to reduce wipe time on large-capacity and multi-drive jobs; verification is scoped to avoid unnecessary full-drive re-reads where cryptographic erase already guarantees destruction.

**Key Features**
- Multi-drive batch wiping
- Scheduled wipe jobs
- Detailed logs and exportable reports
- Cryptographically verified erasure

**Challenges Solved**
Producing verifiable, standards-compliant erasure across drive types (HDD, SSD, NVMe) with different low-level behaviors, while keeping audit reports accurate enough for compliance review.

---

### Deepfake Detection

**Overview**
AI-based image authenticity verification system that analyzes visual and statistical signals to flag synthetic or manipulated media.

**Architecture**
Python inference service (FastAPI) exposing a detection API, backed by trained CNN and Vision Transformer models, with a React frontend for uploading media and reviewing results.

**Tech Stack**
`Python` `OpenCV` `PyTorch` `FastAPI` `React`

**Algorithms**
- Convolutional Neural Networks (CNN)
- Vision Transformer (ViT)
- Face detection and alignment
- Frequency-domain analysis
- Noise-pattern analysis
- Feature extraction and confidence scoring

**Performance Notes**
Combines spatial (CNN/ViT) and frequency-domain features so detection is less dependent on any single artifact, improving robustness against compression and re-encoding.

**Key Features**
- Authenticity confidence score
- Manipulation heatmaps
- Batch image analysis
- REST API for integration into other systems

**Challenges Solved**
Maintaining detection accuracy on heavily compressed or re-encoded media, where standard artifacts can mask or mimic manipulation signatures.

---

### Furniture Manufacturing ERP

**Overview**
Workflow management system for manufacturing operations, covering production tracking, inventory, and reporting in a single platform.

**Architecture**
Full-stack web application with a Next.js/React frontend and a Node.js backend, backed by a relational (SQL) database for production and inventory records.

**Tech Stack**
`Next.js` `React` `Node.js` `SQL`

**Key Features**
- Production tracking dashboard
- Inventory management
- Order and analytics reporting

**Challenges Solved**
Modeling production and inventory state so it stays consistent under concurrent updates from multiple stations and users.

---

## 04 GitHub Statistics

<p align="center">
<img src="https://github-readme-stats.vercel.app/api?username=edixbykv&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" width="48%" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=edixbykv&layout=compact&theme=tokyonight&hide_border=true&langs_count=8" width="38%" />
</p>

<p align="center">
<img src="https://streak-stats.demolab.com/?user=edixbykv&theme=tokyonight&hide_border=true" width="90%" />
</p>

<p align="center">
<img src="https://github-readme-activity-graph.vercel.app/graph?username=edixbykv&theme=tokyo-night&hide_border=true" width="95%" />
</p>

---

## 05 Repository Highlights

| Repository | Description | Stack |
|---|---|---|
| Data Sanitization Suite | Secure, standards-compliant data erasure for Windows | C#, .NET, WPF |
| Deepfake Detection | AI-based image authenticity and manipulation detection | Python, PyTorch, FastAPI |
| Furniture Manufacturing ERP | Production, inventory, and reporting platform | Next.js, Node.js, SQL |

[View all repositories →](https://github.com/edixbykv?tab=repositories)

---

## 06 Development Philosophy

Software should be predictable, verifiable, and easy to reason about.
Correctness and performance take priority over convenience, especially in systems handling security or user data.
Most of the engineering effort goes into testing edge cases, not writing the first version.
Simple, well-tested code beats clever code.
