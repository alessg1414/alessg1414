# Mario Alessandro Garita Guevara

> **Cloud Engineer | Solutions Architect Aspirant | Technical Lead & Infrastructure Engineer**


```

+---------------------------------------------------------------------------------------+
|                                    Career Trajectory                                  |
|                                                                                       |
|   +--------------------------+    +--------------------------+    +-----------------+ |
|   | Software Engineering &   | => | Cloud Infrastructure &   | => | Cloud Solutions | |
|   | Full-Stack Architecture  |    | DevOps Automation        |    | Architecture    | |
|   | (React, .NET, MEP Lead)  |    | (AWS, OCI, GCP, Docker)  |    | (Target Role)   | |
|   +--------------------------+    +--------------------------+    +-----------------+ |
+---------------------------------------------------------------------------------------+

```

> [!NOTE]  
> **Professional Objective**: Cloud Engineering professional transitioning toward Cloud Solutions Architecture. Currently expanding multicloud platform expertise across AWS, OCI, Azure, and GCP while preparing for the **AWS Certified Solutions Architect – Associate (SAA-C03)** designation.

---

## 1. Executive Summary & Professional Profile

Computer Engineering professional and Technical Lead at the **Ministerio de Educación Pública (MEP)**, specializing in system modernization, and secure application architecture. 

* **Engineering Philosophy**: Combines a disciplined full-stack software development background with modern cloud infrastructure, containerization, and high-availability design.
* **Technical Leadership**: Directed a six-developer engineering team on public-sector digital transformation initiatives, taking sole accountability for system stability, CI/CD deployment optimization, and infrastructure refactoring.
* **Cloud & DevOps Orientation**: Active practitioner across multicloud environments (AWS, OCI, GCP, Azure), focusing on automated container deployments, infrastructure provisioning, and fault-tolerant architecture design.

---

## 2. Core Technical Competencies

### Cloud Platforms & Infrastructure
* **Amazon Web Services (AWS)**: EC2, ECS (Fargate), S3, VPC Networking, RDS, IAM
* **Oracle Cloud Infrastructure (OCI)**: Virtual Cloud Networks (VCN), Compute, Security Lists, Subnet Routing, High Availability Quorum Design
* **Google Cloud Platform (GCP)**: Cloud Run (Serverless Containers), Compute Engine, Cloud Storage
* **Microsoft Azure**: Virtual Machines, Virtual Networks (VNets)

### DevOps, Containerization & Systems
* **Containerization**: Docker Engine, Multi-stage builds, Container Registries, Image Footprint Optimization
* **CI/CD & Automation**: GitHub Actions, Pipeline Integration, Bash Scripting, Linux System Administration (Ubuntu/Debian)
* **High Availability & Resilience**: Replica Sets, Active-Passive Architecture, Block-Level Replication, Disaster Recovery Runbooks

### Software Engineering & AI Integration
* **Backend & Web Frameworks**: Python (Flask), C# (.NET 8, ASP.NET Core API), TypeScript, JavaScript, React 19, Next.js 15, Node.js
* **Mobile Engineering**: .NET MAUI (Cross-Platform Android/iOS/Windows), Firebase Integration
* **Database Systems**: MongoDB (Replica Sets & Aggregations), Microsoft SQL Server, PostgreSQL, Relational Schema Design
* **Generative AI & RAG**: Google Gemini API, LlamaIndex (Vector Store Indexing), OpenAI Whisper (`large-v3` CUDA ASR)

---

## 3. Featured Engineering Projects

The following repositories represent core engineering competencies across cloud architecture, artificial intelligence, full-stack development, and cross-platform mobile systems:

---

### 3.1. [weather-api-containerized-serverless](https://github.com/alessg1414/weather-api-containerized-serverless)

> **Serverless Web API, AWS ECS Fargate & CI/CD Pipeline**  
> **Tech Stack:** ASP.NET Core 8 | Docker | AWS ECS (Fargate) | AWS ECR | GitHub Actions | Entity Framework Core 9 | JWT | OpenWeatherMap API

A containerized RESTful Web API engineered for real-time weather data processing, usage auditing, and serverless cloud execution on AWS.
* **Container Optimization:** Built using a multi-stage `Dockerfile` that segregates the SDK build environment from a lightweight, hardened ASP.NET runtime footprint to minimize image size and deployment latency.
* **AWS ECS Fargate Architecture:** Designed for serverless container execution with custom task definitions, IAM execution roles, and secure container registry hosting via **AWS ECR**.
* **Automated CI/CD Pipeline:** Integrated **GitHub Actions** workflows to automatically build, package, and deploy container updates to ECS Fargate with zero-downtime execution upon every repository push.

---

### 3.2. [oci-mongodb-ha-cluster](https://github.com/alessg1414/oci-mongodb-ha-cluster)
> **Cloud High Availability & Disaster Recovery Architecture (OCI)**  
> **Tech Stack**: Oracle Cloud Infrastructure | MongoDB 7.0 | Ubuntu Server | Bash | Cisco Packet Tracer

An active-passive High Availability database cluster hosted on OCI featuring zero data loss (RPO = 0) and sub-minute automated failover.
* **Core Architecture**: Provisioned a multi-fault domain VCN with regional private subnets, implementing customized 2-VM quorum voting logic via a double-vote Arbiter process.
* **Enterprise Baseline**: Designed a supporting Tier III multi-site network topology in Cisco Packet Tracer featuring BGP Multihoming, OSPF full-mesh routing, and LACP EtherChannels.

---

### 3.3. [audiobot-ai-project](https://github.com/alessg1414/audiobot-ai-project)
> **AI-Powered Call Center Audio Analyzer & RAG Engine**  
> **Tech Stack**: Python | OpenAI Whisper | LlamaIndex | Google Gemini 2.5 Flash | React 19 | Flask

An automated speech-to-text pipeline and conversational intelligence tool designed for telephony interaction analysis.
* **Speech-to-Text Pipeline**: GPU-accelerated local transcription via CUDA-enabled OpenAI Whisper `large-v3` with timestamped segment extraction.
* **Grounded RAG Architecture**: Vector index search using LlamaIndex and Gemini embeddings, protected by strict system prompt guardrails against out-of-context hallucinations.

---

### 3.4. [coopdashboard-nextjs](https://github.com/alessg1414/coopdashboard-nextjs)
> **International Cooperation Management Dashboard**  
> **Tech Stack**: Next.js 15 | TypeScript | PrimeReact | Tailwind CSS | Node.js

An enterprise dashboard engineered for tracking international agreement lifecycles, project analytics, and financial reporting.
* **Modular UI Architecture**: Developed with the Next.js 15 App Router and PrimeReact for analytical chart rendering and dynamic data filtering.
* **Lifecycle Tracking**: Manages multi-phase cooperation proposals, stakeholder deliverables, and real-time status transitions.

---

### 3.5. [incident-track-maui](https://github.com/alessg1414/incident-track-maui)
> **Cross-Platform Mobile Incident Tracker**  
> **Tech Stack**: .NET MAUI | C# | Firebase Realtime Database / Auth | XAML

A native cross-platform mobile application for enterprise field incident logging and tracking.
* **Cross-Platform Core**: Built on a single C# / XAML codebase targeting Android, iOS, and Windows desktop runtimes.
* **Security & Operations**: Features role-based access control, real-time ticket state transition updates, comment threads, and advanced status filtering.

---

### 3.6. [socialmedia-project-mern-app](https://github.com/alessg1414/socialmedia-project-mern-app)
> **Full-Stack Social Network Platform**  
> **Tech Stack**: MongoDB | Express.js | React (Vite) | Node.js | Socket.IO

A feature-rich web platform built on the MERN technology stack.
* **Real-Time Communication**: Integrated bidirectional messaging, live activity feeds, and system notifications using Socket.IO websockets.
* **Session Security**: Implemented JWT-based authentication, user profile management, friendship graph relationships, and content moderation rules.

---

## 4. Certifications & Education

* **AWS Certified Solutions Architect – Associate (SAA-C03)** | *Amazon Web Services (In Progress, 2026)*
* **Microsoft Certified: Azure Fundamentals (AZ-900)** | *Microsoft (In Progress, 2026)*
* **Google Cloud Computing Fundamentals** | *Google / PROCOMER Scholarship Program (Expected Oct 2026)*
* **Bachelor of Science in Computer Engineering** | *Universidad Latinoamericana de Ciencia y Tecnología (ULACIT)*

---

## 5. Professional Contact

* **LinkedIn**: [linkedin.com/in/alessandro-garita-guevara-92b515279](https://www.linkedin.com/in/alessandro-garita-guevara-92b515279/)
* **GitHub**: [github.com/alessg1414](https://github.com/alessg1414)

```
