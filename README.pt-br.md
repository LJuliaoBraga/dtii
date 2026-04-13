# DT-MII: Gêmeo Digital para Gestão de Infraestrutura de Internet

[![Language: English](https://img.shields.io/badge/Language-English-blue.svg)](README.md)

Este repositório contém os dados, algoritmos e modelos ontológicos do projeto **DT-MII**. O projeto propõe uma unificação semântica para a Infraestrutura de Internet (II) através do uso de uma Ontologia de Alto Nível baseada na **Unified Foundational Ontology (UFO)**.

## 🎯 Objetivos do Projeto
O DT-MII atua como um **Sistema Imunológico Semântico** para Sistemas Autônomos (AS), sendo capaz de:
* Harmonizar tecnologias heterogêneas (Fibra, Satélite, Wireless) através de uma tríade fundamental: **Node, Connection e Channel**.
* Implementar uma "Constituição Lógica" baseada em Lógica de Descrição (TBox e ABox).
* Mitigar anomalias, como ataques DDoS, através de raciocínio semântico em tempo real.

## 📂 Estrutura do Repositório
* `/docs`: Artigos técnicos (LaTeX), rascunhos do projeto e publicações.
* `/ontology`: Arquivos da Ontologia de Domínio (ODT) (.ttl, .owl) e gUFO.
* `/src`: Scripts Python para Ingestão Semântica, Raciocínio e Mitigação.
* `/topology`: Arquivos de projeto do GNS3 e configurações de rede.
* `/infrastructure`: Dockerfiles e configurações para GraphDB/Fuseki.
* `/data`: Triplas ABox geradas e logs de telemetria.

## 🛠️ Requisitos e Configuração
* **SO:** Windows 11 com WSL2 (Ubuntu 22.04 LTS).
* **Emulação de Rede:** GNS3 (GUI + VM).
* **Design de Ontologia:** Protégé.
* **Programação:** Python 3.12.4+.

## 📄 Documentação
A fundamentação teórica deste projeto está detalhada no artigo:
> *Braga, J. et al. (2026). Digital Twin Project for Internet Infrastructure Management (DT-MII). To be published.*

---
*Desenvolvido por Juliao Braga - Universidade Federal do ABC (UFABC).*
