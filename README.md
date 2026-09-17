# Gabriel V. Allit

**AI Systems Architect | Cognitive Operating Systems & AGI-Oriented Architecture | Autonomy · Edge AI · Geospatial Systems**

Founder of [SALT19](https://salt19.com) and architect of **EvoMind**, a governed Cognitive Operating System built to push beyond isolated model calls toward persistent, inspectable, general-purpose machine cognition.

My primary work is in **AI systems architecture**: reasoning, planning, memory, self/world modeling, learning, transfer, capability composition, desktop and tool operation, verification, proof-oriented evaluation, and governed improvement. Around that core I also build advanced autonomy, edge-AI, UAS, geospatial, photogrammetry, resilient-PNT, local coding-agent, machine-commerce, and production software systems.

Florida · U.S. Navy veteran · FAA Part 107 Remote Pilot

> **Access note:** a significant portion of my active engineering work is private. Selected repositories, architecture, validation evidence, demonstrations, and source can be made available **on request to approved reviewers, employers, collaborators, customers, or research partners**, subject to confidentiality, security, export/IP, and project-specific access constraints.

> **Claim boundary:** EvoMind is an AGI-oriented cognitive architecture with substantial internal engineering and benchmark evidence. I do **not** present it as independently certified or independently demonstrated AGI. The objective is to build and test the architecture required for increasingly general, persistent, self-correcting cognition while keeping evidence, authority, provenance, and failure modes explicit.

## Primary work — EvoMind Cognitive Operating System

**EvoMind is the central body of my work.** It is a local-first cognitive operating system and research platform designed around a question larger than “which model should answer this prompt?”:

**How do you build a machine that can maintain goals, reason over state, plan, act, verify what actually happened, learn from verified experience, transfer useful structure, understand its own capabilities, and improve without silently acquiring authority it was never given?**

The canonical cognitive control spine is organized around:

```text
Operator intent / persistent goals
            ↓
Self state + world state + memory
            ↓
Reasoning + planning + prediction
            ↓
Capability composition + model routing
            ↓
Governance + execution authority
            ↓
Tools / desktop / environment execution
            ↓
Fresh semantic verification
            ↓
Receipts + artifacts + provenance
            ↓
Memory admission + experience reuse
            ↓
Learning / transfer / future planning
```

### Core cognitive capabilities

- **Persistent goals and long-running task state** rather than isolated prompt/response interactions.
- **Reasoning and planning** over explicit goals, capabilities, state, constraints, and recovery paths.
- **Memory architecture** that distinguishes observations, verified state, reusable experience, and durable belief.
- **Self-modeling and capability awareness** for representing what the system can do, what it has evidence for, and where uncertainty remains.
- **World-state integration and causal learning** so verified outcomes can change future predictions rather than simply being logged.
- **Predict → act → verify → score → revise loops** through the real governed execution spine.
- **Capability composition and model routing** across local and external intelligence sources without equating model output with execution authority.
- **Desktop, browser, tool, and environment operation** so cognition can terminate in verifiable work products rather than text alone.
- **Verified Semantic Transitions (VST)** so action completion is treated as evidence, while durable belief advances only after the required postcondition is freshly verified.
- **Governed experience compounding** so successful prior work can be reused without silently granting new permissions.
- **Transfer and abstraction research** aimed at extracting reusable structure instead of benchmark-specific shortcuts.
- **Bounded self-improvement** with explicit validation, regression evidence, and authority boundaries.
- **Proof- and evidence-oriented engineering** using receipts, manifests, hashes, replay, benchmark harnesses, formal/proof tooling where useful, and reproducible audit artifacts.

### Evidence posture

EvoMind is not a conceptual slide deck or a thin LLM wrapper. It is a large, active Python cognitive system with a canonical runtime, benchmark infrastructure, governance, memory, planning, world-model, self-model, desktop-operation, verification, learning, and evidence subsystems.

Selected internal evidence includes:

- a frozen **MiniWoB++ 407/625 (65.12%)** internal regression result after progressive capability repair;
- external Windows-agent benchmark integration and diagnostic work against Microsoft WindowsAgentArena;
- a live **predict → act → verify → score → revise** loop whose learned outcome model survives restart and feeds an existing cognitive uncertainty signal;
- VST-based fresh semantic verification and durable transition admission;
- governed experience reuse, artifact lineage, receipts, and execution-denial evidence;
- ARC-oriented causal-learning, belief-revision, structural-consumption, and transfer experiments with explicit negative findings retained rather than rewritten;
- ongoing gap reconciliation across long-horizon continuity, richer world prediction, self-model calibration, transfer, context assembly, and independent replication.

Research and public orientation:

- [EvoMind research hub](https://salt19.com/research)
- [EvoMind validation record](https://salt19.com/validation-report)
- [EvoMind software and cognitive architecture](https://doi.org/10.5281/zenodo.20580153)
- [Verified Semantic Transitions](https://doi.org/10.5281/zenodo.21270654)
- [Governed Experience Compounding](https://doi.org/10.5281/zenodo.21881379)
- [From Intent to Verified Work Products](https://doi.org/10.5281/zenodo.21957527)

## Advanced systems portfolio

EvoMind is the primary research program, but the surrounding portfolio is intentionally broad. I build complete systems across cognition, robotics, edge inference, desktop software, geospatial engineering, cloud infrastructure, and machine-to-machine services.

| System | Scope and current posture |
|---|---|
| **EvoMind CogOS** *(private core + public research surfaces)* | AGI-oriented cognitive operating system spanning persistent goals, planning, reasoning, memory, self/world models, causal prediction, governed execution, desktop operation, fresh verification, learning, transfer, evidence, and bounded improvement. Selected private source and evidence can be reviewed by approved parties. |
| **TACWING X** *(private; controlled review available)* | A substantial Android edge-C2 and operator-awareness platform with one canonical runtime across **DJI MSDK V4 and MAVLink v2** compositions. Current `main` includes native frame ingest, offline ONNX perception, operator-authorized ActiveTrack integration, MAVLink telemetry/commands/video discovery, resilient localization, optical VIO, camera/terrain registration, ECS-backed multimodal world modeling, low-bandwidth federation, governed command authority, ROS 2 bridge tooling, and dedicated Windows/Linux self-hosted CI. Both Android compositions and native ABIs build in the validated toolchain; the remaining major gate is powered-aircraft hardware validation. |
| **CloneCode** *(private; controlled review available)* | Windows-first local AI coding workspace with Ask/Plan/Agent/Sandbox-Agent modes, local-model routing, sparse repository cognition, LSP intelligence, inline completion, governed autonomous coding, RED/GREEN verification, independent review, Git worktree isolation, optional Windows Sandbox containment, skills/plugins/connectors/MCP, local memory, browser testing, and empirical local-model/agent benchmarking. |
| **DroneMesh by SALT19** *(private product)* | Local-first photogrammetry workstation using Electron + Python with MicMac/GDAL/PDAL processing, durable checkpoints, adaptive chunking, orthomosaics, DSM/DEM/DTM, point clouds, meshes, contours, reporting, offline handover packages, REST/MCP automation, local Qwen assistance, and a Cloudflare/D1 licensing control plane. |
| **Aether / AetherCoach** *(public + private development surfaces)* | Local desktop AI systems spanning Electron/TypeScript, Rust/native audio paths, screen capture, OCR, local/on-device speech recognition, screenshot understanding, retrieval, SQLite-backed memory, reference-file context, real-time assistance, local Ollama operation, and multi-provider model orchestration. |
| [SALT19 Agent Utility Grid](https://salt19.com/agent-utility-grid/) | Machine-to-machine utility and commerce infrastructure using MCP/x402 patterns, Cloudflare Workers/D1, machine-readable outputs, authorization evidence, Base USDC settlement paths, reconciliation, and automated service execution. [Research DOI](https://doi.org/10.5281/zenodo.22102248). |
| [AeroClear](https://aeroclear.salt19.com/?utm_source=github&utm_medium=profile&utm_campaign=portfolio&utm_content=flagship_systems) | UAS flight-intelligence and mission-readiness platform combining airspace, weather, operational context, production web infrastructure, D1-backed state, and explainable flight decision support. |
| [AMEP-1 — Adaptive Maritime Estimation and PNT](https://github.com/GabrielAllit1/AMEP) | Resilient multisensor navigation and integrity research for GNSS-degraded/GNSS-denied operation. Current research/SIL architecture includes time alignment, source/dependency contracts, a replaceable estimator backend, seven-state maritime EKF reference, cross-source consistency, health/integrity supervision, deterministic replay, hash-chained evidence, and explicit navigation-authority degradation. [Wiki](https://github.com/GabrielAllit1/AMEP/wiki) · [DOI](https://doi.org/10.5281/zenodo.22561851). |
| [UAS Thermal Analysis](https://github.com/GabrielAllit1/UAS-Thermal-Analysis-Tool) | Local-first thermal intelligence platform with radiometric quality gates, GeoTIFF/DJI DIRP adapters, anomaly analysis, measurements, GIS exports, reporting, optional local-model enrichment, and SHA-256 deliverable provenance. |
| [UAS Survey Tool](https://github.com/GabrielAllit1/uas-survey-tool) | Desktop survey-planning and QA/QC application with terrain-aware calculations, DEM/DSM handling, GCP/VCP workflows, KML/KMZ overlays, geospatial processing, and professional field/reporting outputs. |
| [FAM Spectral Reconstruction Engine](https://github.com/GabrielAllit1/FAM-Spectral-Reconstruction-Engine) | Scientific/GIS tooling for virtual spectral reconstruction, virtual NIR and vegetation indices, fractal stress indicators, graphon-based structural analysis, tiled orthomosaic processing, and technical reporting. |
| [SignalLoom InvoiceOps](https://github.com/GabrielAllit1/SignalLoom) | Local-first document/invoice extraction, review, exception handling, approval preparation, AP handoff, and local-model-assisted workflow automation. |
| [Recruiter.ai](https://github.com/GabrielAllit1/Recruiter.ai) | Privacy-focused browser tooling for local resume parsing, job matching, freshness signals, and explainable fit scoring. |
| [Patriot Claim Tracker](https://github.com/GabrielAllit1/Patriot-Claim-Tracker) | Local-first browser application for organizing authorized VA.gov information without requiring a SALT19-hosted personal-data service. |

## Engineering breadth

**AI systems and cognition**  
`Cognitive architectures` · `Agentic systems` · `Persistent goals` · `Reasoning` · `Planning` · `Memory` · `World models` · `Self-models` · `Causal learning` · `Capability composition` · `Model routing` · `Transfer` · `Verification` · `Governed self-improvement` · `Desktop agents` · `RAG` · `Local inference`

**Languages**  
`Python` · `C++` · `TypeScript` · `JavaScript / Node.js` · `Kotlin` · `Rust` · `SQL` · `HTML / CSS`

**AI, perception and local inference**  
`PyTorch` · `OpenCV` · `ONNX Runtime` · `Ollama` · `Whisper-class STT` · `OCR` · `Embeddings / retrieval` · `NumPy` · `SciPy` · `Pandas` · `CUDA`

**Robotics, UAS and edge autonomy**  
`DJI MSDK` · `MAVLink v2` · `VIO` · `Resilient localization / PNT` · `Multisensor fusion` · `EKF / nonlinear estimation` · `World models` · `Android SDK / NDK` · `JNI` · `CMake` · `ROS 2 bridge tooling` · `NVIDIA Jetson` · `Operator-authorized autonomy`

**Geospatial, remote sensing and imaging**  
`GDAL / PROJ` · `Rasterio` · `GeoPandas` · `Fiona` · `Shapely` · `PyProj` · `LiDAR` · `Photogrammetry` · `Thermal radiometry` · `GeoTIFF` · `DEM / DSM / DTM / CHM` · `KML / KMZ` · `Terrain registration`

**Desktop, backend and infrastructure**  
`Electron` · `PyQt` · `FastAPI` · `Cloudflare Workers` · `D1` · `SQLite / better-sqlite3` · `PostgreSQL` · `Stripe` · `MCP` · `x402` · `GitHub Actions` · `Self-hosted CI runners` · `PyInstaller` · `Windows packaging`

## Research and publications

- [EvoMind: software and cognitive-architecture publication](https://doi.org/10.5281/zenodo.20580153)
- [Verified Semantic Transitions (VST)](https://doi.org/10.5281/zenodo.21270654) — belief-gated state transitions where action completion is evidence and durable belief advances only after fresh semantic verification.
- [Governed Experience Compounding](https://doi.org/10.5281/zenodo.21881379) — controlled reuse of verified experience under explicit authority and provenance constraints.
- [From Intent to Verified Work Products](https://doi.org/10.5281/zenodo.21957527) — architecture for carrying intent through execution into verifiable artifacts.
- [SALT19 Agent Utility Grid](https://doi.org/10.5281/zenodo.22102248) — machine-readable agent utilities, governance, and machine-commerce infrastructure.
- [Allit Geoid Truth Projection (AGTP-1)](https://doi.org/10.5281/zenodo.22385043) — reproducible interrupted equal-area world-projection research with seam audits, distortion benchmarks, and falsification criteria.
- [AMEP-1 — Adaptive Maritime Estimation and PNT](https://doi.org/10.5281/zenodo.22561851) — resilient multisensor navigation and integrity research with explicit negative findings and production-hardening boundaries.

## Systems philosophy

Across cognition, robotics, developer tooling, geospatial systems, and production applications, I tend to build around the same principles:

- **Model output is evidence, not authority.**
- **Action completion is not the same as verified success.**
- **Durable belief should follow fresh verification.**
- **Authority boundaries should remain explicit across the entire stack.**
- **Failures and negative results belong in the evidence record.**
- **Local-first operation is valuable when it improves privacy, inspectability, latency, or resilience.**
- **Reusable system boundaries matter more than benchmark-specific shortcuts.**
- **Internal validation and independent validation are different things.**
- **A serious AI system needs cognition, execution, memory, learning, verification, provenance, and governance—not just a stronger prompt.**

## Professional and research links

- [SALT19](https://salt19.com)
- [Founder portfolio](https://salt19.com/founder)
- [EvoMind research hub](https://salt19.com/research)
- [EvoMind validation record](https://salt19.com/validation-report)
- [AMEP repository](https://github.com/GabrielAllit1/AMEP)
- [LinkedIn](https://www.linkedin.com/in/gabrielallit/)
- [ORCID](https://orcid.org/0009-0008-2365-226X)

## Current direction

My main objective is to push **EvoMind CogOS** toward increasingly general cognition by closing the remaining gaps between:

**goal → perception/state → reasoning → planning → prediction → action → verification → learning → transfer → self-modeling → governed improvement**

At the same time, systems such as TACWING X, CloneCode, DroneMesh, Aether, AeroClear, AMEP, and the SALT19 Agent Utility Grid provide very different real engineering environments in which those same architectural principles can be tested: desktop software, coding agents, robotics, UAS, multimodal perception, geospatial processing, resilient navigation, edge inference, and production infrastructure.

I am most interested in technically demanding work involving **AI systems architecture, cognitive operating systems, advanced agentic systems, AGI-oriented research, autonomy, robotics, edge AI, perception, geospatial intelligence, and integrated software/hardware systems**.
