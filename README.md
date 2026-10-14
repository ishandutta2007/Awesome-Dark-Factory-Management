# Awesome-Dark-Factory-Management

## Top Dark Factory Management Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Lights-Out Manufacturing, Autonomous Quality Inspection & Unattended Production*  

**Last updated: March 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Dark Factory Management**. These tools enable manufacturers to run production with minimal or zero human presence on the floor—coordinating robots, vision systems, and MES layers autonomously while maintaining quality, traceability, and OEE visibility.



**Examples** include StrongDM, Cognite, Instrumental, Bright Machines, Augmentir, Plex Systems, Tulip Interfaces, Drishti, Arch Systems, and Retrocausal (the category leaders).



**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, agent-native MES, and open visual inspection pipelines—ideal for manufacturing engineers, plant operators, and developers seeking transparent, vendor-independent dark factory infrastructure.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Cognite Data Fusion](https://www.cognite.com/)**  

  Industrial DataOps platform unifying OT and IT data for AI-driven operations. Features industrial knowledge graph, contextualized data models, and AI copilots for production optimization.



- **[Instrumental](https://instrumental.com/)**  

  AI-powered visual inspection platform for manufacturing. Uses computer vision to detect defects on production lines in real time, with active learning to improve detection over time.



- **[Bright Machines](https://www.brightmachines.com/)**  

  Intelligent automation platform combining robotics, machine vision, and software for electronics assembly. Enables flexible, software-defined manufacturing cells.



- **[Augmentir](https://www.augmentir.com/)**  

  AI-powered connected worker platform for frontline operations. Features guided workflows, skills management, and real-time production insights.



- **[Plex Systems](https://www.plex.com/)**  

  Cloud ERP and MES for manufacturing. Features production monitoring, quality management, and traceability for discrete and process manufacturing.



- **[Tulip Interfaces](https://tulip.co/)**  

  Frontline operations platform for manufacturing. Enables no-code app building for production tracking, quality inspection, and machine monitoring.



- **[Drishti](https://drishti.com/)**  

  AI-powered video analytics for manual assembly lines. Provides real-time cycle time analysis, defect detection, and workstation-level insights without wearables.



- **[Arch Systems](https://archsys.io/)**  

  Machine data platform for electronics manufacturing. Connects SMT, test, and assembly equipment for real-time OEE, traceability, and analytics.



- **[Retrocausal](https://retrocausal.ai/)**  

  AI copilot for manufacturing assembly. Provides real-time work instructions, error-proofing, and process mining from video feeds.



- **[StrongDM](https://www.strongdm.com/)**  

  Infrastructure access platform ensuring secure, auditable access to production systems. Relevant for dark factories requiring zero-trust access to critical OT infrastructure.



## Open-Source GitHub Projects



- **[FactorySemantics MES](https://github.com/factorysemantics/factorysemantics-mes)**  

  An open-source, modular, **agent-native Manufacturing Execution System** (license: Apache-2.0) designed for small-to-mid plants. Kernel + modules architecture with ISA-95 data model, PackML machine states, and ISO 22400 KPIs. **Agent-native**: every function callable via REST and MCP with read tools free, command tools idempotent and approval-gated. Every action lands in an **append-only audit spine**. Runs anywhere from SQLite on a laptop to Docker Compose in a plant. **Simulation-first**: CI runs a full fake plant with deterministic six-station line over real OPC UA server. **The most modern open-source MES for agent-driven production** .



- **[OpenCore MES](https://github.com/opencore-mes/opencore-mes)**  

  Low-code MES for advanced manufacturing from small plants to **300 mm fabs** (license: Apache-2.0). Engineers design objects, states, roles, rules, screens, transactions and services in a browser designer. **Every change goes through design → review → approval → execution** before reaching the plant. Every write goes through the same policies, rules, and **hash-chained audit trail**. Equipment adapters build on published, versioned contracts. Node 24+ and PostgreSQL required. **The most governance-focused open-source MES available** .



- **[Carbon](https://github.com/PabloOyarzo/carbon)**  

  Open-source manufacturing ERP/MES/QMS (license: AGPL-3.0). Features ERP, MES, QMS, custom fields, nested BoM, traceability, MRP, configurator, MCP client/server, API, and webhooks. Built with Remix, TypeScript, Supabase, and Tailwind. **Full-stack type safety** from database to UI. Unified auth and permissions across apps with ABAC, RBAC, and row-level security. **Realtime database subscriptions**. **The most complete open-source manufacturing suite for complex assembly and configure-to-order** .



- **[qcadoo MES](https://github.com/qcadoo/mes)**  

  Friendly web manufacturing software for small and medium companies (license: AGPLv3). 940+ GitHub stars. Combines functions of large ERP systems adapted for SMEs. Community version open source; commercial version adds full support, SaaS deployment, REST API, ERP/SCADA integrations, Gantt planning, and maintenance planning. **The most mature and widely adopted open-source MES for SMEs** .



- **[OSOlogic Platform](https://github.com/OSOlogic/platform)**  

  Open-source industrial controller platform (license: AGPL-3.0) turning any machine—from tiny MCU to server—into a **real-time industrial controller you own**. Program in Ladder, Structured Text, or any modern language. **Every value is a tag** accessible via SQL, REST, OPC-UA, MQTT, or AI agent. SQL and REST are first-class control interfaces. Runs on PREEMPT_RT Linux, RP2040, STM32, ESP32. **The most ambitious open-source alternative to proprietary PLCs** .



- **[Unified Manufacturing Hub](https://github.com/united-manufacturing-hub/united-manufacturing-hub)**  

  Open-source toolkit to build reliable and secure **Industrial IoT platforms** (license varies). 271+ GitHub stars. Provides OPC UA gateway to MQTT/GraphQL, manufacturing line simulator with PackML over MQTT, and unified namespace for IIoT transformation. **The most comprehensive open-source IIoT toolkit for factory connectivity** .



- **[Agrync](https://github.com/ManuelMuRodriguez/Agrync)**  

  Open-source platform unifying Modbus, OPC-UA, and FIWARE protocols into a single web interface for sensor management (license varies). Validated in real agro-industrial facility managing **1,200+ data points** continuously. Data capture rate 98.2%, notification latency P95 84ms, core stack ~406 MiB RAM. **The most production-validated open-source industrial IoT integration layer** .



- **[Anomalib](https://github.com/openvinotoolkit/anomalib)**  

  Open-source anomaly detection library with state-of-the-art algorithms (license: Apache-2.0). **6,211+ GitHub stars**. Features experiment management, hyperparameter optimization, and edge inference. Supports PaDiM, PatchCore, and other industrial anomaly detection methods. **The most widely adopted open-source library for visual defect detection** .



- **[Open AOI](https://github.com/open-aoi/open-aoi)**  

  Open-source Automated Optical Inspection platform designed for industrial inspection tasks (license varies). Simple installation, graphical user interface, customization support, and ROS-powered performance. Covers wide range of inspection applications. **The most complete open-source AOI solution** .



### Additional Strong Open-Source Options



- **[JSON-SCADA](https://github.com/riclolsen/json-scada)** — Portable and scalable SCADA/IIoT-I4.0/Gateway platform (license varies). All-in-one Docker image with MongoDB, PostgreSQL/TimescaleDB, Grafana, IEC 60870-5-104, DNP3, OPC UA, MQTT Sparkplug B, and Metabase. **The most comprehensive open-source SCADA stack** .

- **[Industrial-ML](https://github.com/YKatser/Industrial-ML)** — Curated overview of cases, public datasets, books, and academic papers for applying ML in industrial applications. **Essential reference for industrial ML projects** .

- **[InfluxDB 3 IIoT Reference Architecture](https://github.com/influxdata/influxdb3_iiot_reference_architecture)** — Runnable reference architecture simulating automotive assembly plant (1 plant × 3 lines × 8 stations = 24 machines, ~300 points/sec). Includes Processing Engine Python plugins, Last Value Cache, and andon board UI. `docker compose up` in ~2 minutes .

- **[Albumentations](https://github.com/albumentations-team/albumentations)** — Fast image augmentation library (MIT) used in 84+ public industrial/ manufacturing repos for defect detection and quality inspection .

- Community **n8n** workflows for production alerting and dark factory orchestration automation.



**Frameworks for building custom systems**: Combine **FactorySemantics MES** or **OpenCore MES** as the agent-native execution layer with **OSOlogic** for open PLC control, **Anomalib** or **Open AOI** for visual inspection, **Unified Manufacturing Hub** for IIoT connectivity, and **PostgreSQL + InfluxDB** for persistence—creating a fully self-hosted, enterprise-grade dark factory platform.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Dark factory systems controlling production equipment must comply with industrial safety regulations (OSHA, ISO 13849, IEC 61508) and implement rigorous safety validation before unattended operation.

- **Open-source dark factory management is emerging, not mature.** FactorySemantics MES and OpenCore MES are recent, ambitious projects—not yet proven at scale . qcadoo MES is mature for SMEs but lacks agent-native and lights-out capabilities . **No single open-source tool provides the end-to-end dark factory orchestration of Cognite or Bright Machines.** Integration work is required.

- **Agent-native MES introduces new safety surfaces.** FactorySemantics makes every function callable via MCP with approval gates and audit spines . OpenCore MES requires design → review → approval → execution for every change . These are essential patterns—never deploy autonomous production control without deterministic policy enforcement.

- **Simulation-first is the correct approach.** FactorySemantics runs a full fake plant in CI with deterministic six-station line and scripted failures . Test dark factory workflows in simulation before touching real equipment.

- **Visual inspection is the mature open-source layer.** Anomalib (6,211+ stars) and Open AOI provide production-grade defect detection . These can serve as the quality layer for dark factory operations.

- Self-hosted open-source solutions require proper security hardening, OT/IT network segmentation, and ongoing maintenance. Dark factories are safety-critical—validation, redundancy, and fail-safe mechanisms are non-negotiable.
