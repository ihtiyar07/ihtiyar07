<div align="center">

# Ahmet İhtiyar 👋
### Senior Systems & Backend Engineer | Edge-to-Cloud Architect

[![Status](https://img.shields.io/badge/Status-Open_for_Projects_%26_Architecture_Advisory-00C853?style=for-the-badge&logo=statuspage&logoColor=white)](#)
[![Location](https://img.shields.io/badge/Location-Turkey_(Open_to_Global_Remote)-1E88E5?style=for-the-badge&logo=googlemaps&logoColor=white)](#)
[![Email](https://img.shields.io/badge/Email-ahmetihtiyar1453%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:ahmetihtiyar1453@gmail.com)

<br/>

*Bridging low-level hardware edge computing (ESP32, Modbus RTU/TCP, 4G LTE) to high-throughput distributed microservices (Java 21 Spring Boot, C# .NET), enterprise metadata lineage (MetaDB, Memgraph Graph DB, PostgreSQL), and virtualized server infrastructure (Proxmox VE, Fedora Linux, Docker).*

---

</div>

## 🧭 About Me

I am a full-spectrum systems and backend engineer with deep expertise across the entire execution stack. My focus is on **high-reliability distributed architectures**, **industrial IoT telematics**, and **zero-impact metadata pipelines** on mission-critical enterprise systems.

- ⚡ **Industrial IoT & Firmware:** Engineering resilient firmware on ESP32 (C/C++) with FreeRTOS, Modbus RTU (RS-485)/TCP for industrial cooling/telemetry, and automatic 4G/GSM cellular failover with local flash ring-buffers.
- 🏛️ **Distributed Backends & Microservices:** Designing high-concurrency payment engines, reactive microservices, and idempotent message-driven pipelines with Java 21 / Spring Boot 3, C# .NET, Redis distributed locks, and RabbitMQ.
- 🧬 **Enterprise Data Lineage & Metadata (MetaDB):** Architecting multi-tenant metadata platforms ingesting Oracle, MSSQL, PostgreSQL, and ODI into canonical models; rendering lineage graphs via Memgraph (Bolt/Cypher) with strict **Zero-Impact Guardrails** (catalog-only statistics) on multi-terabyte production DBs.
- 🛡️ **DevOps, Hypervisors & Security:** Operating Proxmox VE 8 virtualization clusters (KVM & LXC) backed by ZFS and PBS automated backups; hardening Fedora Linux hosts and federating IAM/SSO via Keycloak (OAuth2/OIDC).

---

## 🛠️ Technical Stack & Engineering Arsenal

<div align="center">

### 💻 Languages & Distributed Backend
![Java](https://img.shields.io/badge/Java_21-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot_3-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![C#](https://img.shields.io/badge/C%23_.NET_8%2F10-239120?style=flat-square&logo=csharp&logoColor=white)
![Python](https://img.shields.io/badge/Python_3.11+-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![C++](https://img.shields.io/badge/C%2B%2B_Embedded-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React_19-61DAFB?style=flat-square&logo=react&logoColor=black)

### 📡 Industrial IoT & Edge Protocols
![ESP32](https://img.shields.io/badge/ESP32-E7352C?style=flat-square&logo=espressif&logoColor=white)
![FreeRTOS](https://img.shields.io/badge/FreeRTOS-00A98F?style=flat-square&logo=arm&logoColor=white)
![Modbus](https://img.shields.io/badge/Modbus_RTU_%2F_TCP-004488?style=flat-square&logoColor=white)
![MQTT](https://img.shields.io/badge/MQTT_over_TLS-660066?style=flat-square&logo=mqtt&logoColor=white)
![RS485](https://img.shields.io/badge/RS--485_Industrial-4A4A4A?style=flat-square&logoColor=white)
![4G LTE](https://img.shields.io/badge/4G_LTE_Cellular-107C41?style=flat-square&logoColor=white)

### 🗄️ Databases, Graph & Streaming
![PostgreSQL](https://img.shields.io/badge/PostgreSQL_16+-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Memgraph](https://img.shields.io/badge/Memgraph_Graph_DB-00D4FF?style=flat-square&logoColor=black)
![TimescaleDB](https://img.shields.io/badge/TimescaleDB-FDB515?style=flat-square&logo=timescale&logoColor=black)
![Redis](https://img.shields.io/badge/Redis_Distributed_Lock-DC382D?style=flat-square&logo=redis&logoColor=white)
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=flat-square&logo=rabbitmq&logoColor=white)
![SQL Server](https://img.shields.io/badge/MSSQL_Server-CC292B?style=flat-square&logo=microsoftsqlserver&logoColor=white)

### ⚙️ DevOps, Virtualization & IAM
![Proxmox VE](https://img.shields.io/badge/Proxmox_VE_8-E57000?style=flat-square&logo=proxmox&logoColor=white)
![Fedora Linux](https://img.shields.io/badge/Fedora_Linux-51A2DA?style=flat-square&logo=fedora&logoColor=white)
![Docker](https://img.shields.io/badge/Docker_%26_Compose-2496ED?style=flat-square&logo=docker&logoColor=white)
![Keycloak](https://img.shields.io/badge/Keycloak_SSO_IAM-4D4D4D?style=flat-square&logo=redhat&logoColor=white)
![OAuth2](https://img.shields.io/badge/OAuth2_%2F_OIDC-EB5424?style=flat-square&logo=auth0&logoColor=white)
![ZFS](https://img.shields.io/badge/ZFS_Storage_Pools-005B94?style=flat-square&logoColor=white)

</div>

---

## 🏛️ Architectural Pillars & Key Systems

```
 [ Field Edge ]              [ Transport & Messaging ]           [ Enterprise Services ]             [ Infrastructure ]
 ┌──────────────┐            ┌──────────────────────┐            ┌────────────────────────┐         ┌──────────────────┐
 │ ESP32 Modbus │ ──MQTT/TLS─► RabbitMQ / AMQP Mesh │ ──Event───►│ Spring Boot 3 Microsvc │         │ Proxmox VE 8     │
 │ RS-485 Nodes │            └──────────────────────┘            │ .NET Core Payment Mesh │         │ (KVM / LXC / ZFS)│
 └──────────────┘                       │                        └────────────────────────┘         └──────────────────┘
        │ GSM 4G Failover               │                                     │                              │
 ┌──────────────┐            ┌──────────────────────┐            ┌────────────────────────┐         ┌──────────────────┐
 │ Flash Buffer │            │ TimescaleDB (Metrics)│            │ MetaDB + Memgraph Bolt │◄────────┤ Keycloak IAM SSO │
 │ Ring Storage │            │ Redis (Dist. Locks)  │            │ (Zero-Lock Data Lineage│         │ Multi-Realm OIDC │
 └──────────────┘            └──────────────────────┘            └────────────────────────┘         └──────────────────┘
```

### 1. 🧬 MetaDB — Enterprise Multi-Tenant Data Lineage Platform
- **Problem:** Extracting metadata from multi-terabyte production DBs (Oracle, MSSQL, PostgreSQL, ODI) without locking tables or degrading performance.
- **Solution:** Strict **Zero-Impact Guardrail** utilizing internal catalog statistics (`pg_class.reltuples`, Oracle `ALL_TABLES.NUM_ROWS`) rather than full table scans. Normalizes data through an Ingestion -> Transformation -> Global (GLB) pipeline, rendering lineage graphs in **Memgraph** via Cypher Bolt.

### 2. ❄️ Industrial Cold-Chain & Cooling IoT Gateway (ESP32)
- **Problem:** Mission-critical industrial refrigeration units requiring 24/7 telemetry monitoring under harsh factory conditions with intermittent network connectivity.
- **Solution:** Custom **ESP32 FreeRTOS** firmware interfacing with chiller controllers via **Modbus RTU (RS-485)** and TCP. Equipped with hardware watchdogs, an on-chip flash ring buffer (zero data loss during outages), and automatic **Ethernet -> 4G/GSM LTE** failover.

### 3. 💳 Centralized Multi-Client Payment & Transaction Engine
- **Problem:** Routing high-volume financial transactions across multiple banking virtual POS providers for heterogeneous consumer apps.
- **Solution:** Unified payment engine engineered in **C# .NET & Spring Boot WebFlux**. Features hierarchical Client/App tenant isolation, strict idempotent request execution, distributed Redis locking, and asynchronous audit reconciliation.

### 4. 🖥️ Proxmox VE Virtualization Cluster & Fedora Infrastructure
- **Problem:** Reproducible, resilient, and isolated multi-tier environments for microservices, message brokers, and graph databases.
- **Solution:** Enterprise homelab running on **Proxmox VE 8** (KVM virtual machines & LXC containers) over ZFS pools, backed up via automated **Proxmox Backup Server (PBS)** snapshots, fronted by Nginx reverse proxy and secured with WireGuard.

---

## 📊 GitHub Analytics

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=ihtiyar07&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0D1117" alt="Ahmet's GitHub Stats" height="165" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=ihtiyar07&layout=compact&theme=tokyonight&hide_border=true&bg_color=0D1117" alt="Top Languages" height="165" />

</div>

---

## 📬 Let's Connect

Whether you want to discuss distributed backend architecture, industrial IoT firmware, high-scale metadata lineage, or Proxmox infrastructure:

- ✉️ **Email:** [ahmetihtiyar1453@gmail.com](mailto:ahmetihtiyar1453@gmail.com)
- 💼 **LinkedIn:** [Ahmet İhtiyar](https://www.linkedin.com) *(Update with your direct LinkedIn URL)*
- 🌐 **Portfolio & Architecture Sandbox:** [ihtiyar07](https://github.com/ihtiyar07)

<div align="center">
  <sub>Crafted with engineering precision • Designed for reliability & high-throughput systems</sub>
</div>
