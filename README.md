# DT-II: Ontologies, Digital Twin and Intelligent Telemetry for Internet Infrastructure

[![Language: Portuguese](https://img.shields.io/badge/Language-Portuguese-green.svg)](README.pt-br.md)

This repository contains the data, algorithms, and ontological models for the **DT-MII** project. This project proposes a semantic unification for Internet Infrastructure (II) using a High-Level Ontology grounded in the **Unified Foundational Ontology (UFO)**.

## 🎯 Project Goals
The DT-MII acts as a **Semantic Immune System** for Autonomous Systems (AS), capable of:
* Harmonizing heterogeneous technologies (Fiber, Satellite, Wireless) through a fundamental triad: **Node, Connection, and Channel**.
* Implementing a "Logical Constitution" based on Description Logic (TBox and ABox).
* Mitigating anomalies, such as DDoS attacks, through real-time semantic reasoning.

## 📂 Repository Structure
* `/docs`: Technical papers (LaTeX), project drafts, and publications.
* `/ontology`: The Domain Ontology (ODT) files (.ttl, .owl) and gUFO imports.
* `/src`: Python scripts for Semantic Ingestion, Reasoning, and Mitigation.
* `/topology`: GNS3 project files and network configurations.
* `/infrastructure`: Dockerfiles and setup for GraphDB/Fuseki.
* `/data`: Generated ABox triples and telemetry logs.

## 🛠️ Requirements & Setup
* **OS:** Windows 11 with WSL2 (Ubuntu 22.04 LTS).
* **Network Emulation:** GNS3 (GUI + VM).
* **Ontology Design:** Protégé.
* **Programming:** Python 3.12.4+.

## 📄 Documentation
The theoretical foundation of this project is detailed in the paper:
> *Braga, J. et al. (2026). Digital Twin Project for Internet Infrastructure Management (DT-MII).*

---
*Developed by Juliao Braga - Federal University of ABC (UFABC).*
