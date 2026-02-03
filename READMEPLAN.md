
# 🔐 AI-Powered Cybersecurity Anomaly Detection Platform

## 📌 Project Overview
This project is an industry-grade AI-powered cybersecurity anomaly detection platform designed to identify suspicious system and network behavior using unsupervised machine learning. The system learns normal behavior from logs and detects deviations that may indicate zero-day attacks, insider threats, or malware activity.

This repository follows a **strict day-by-day execution plan**, similar to how projects are executed in real-world Security Operations Centers (SOC).

---

## 📊 Current Progress Status
- ✅ **Day 1 completed**
- 🔄 **Day 2 starting**
- ❌ Day 3 onwards not started

> A day is marked complete only if **code + documentation + validation** are finished.

---

## 📅 Detailed Day-by-Day Execution Plan (45 Days)

---

## 🟢 DAY 1 – Cybersecurity Anomaly Detection Fundamentals (COMPLETED)

### Objectives
- Understand anomaly-based vs rule-based security
- Identify limitations of signature-based detection
- Define project motivation and scope

### Activities
- Studied SOC architectures
- Learned zero-day attack concepts
- Analyzed insider threat scenarios

### Deliverables
- Problem statement
- Objectives
- Project overview

---

## 🟡 DAY 2 – Linux Log Sources & Security Semantics

### Objectives
- Understand Linux system logs
- Identify security-relevant events
- Learn normal vs abnormal behavior

### Log Sources
- auth.log
- syslog
- sudo logs
- process logs

### Deliverables
- docs/log-sources.md
- docs/security-events.md

---

## 🔵 DAY 3 – Log Schema Design & Event Modeling

### Objectives
- Convert raw logs into structured events

### Deliverables
- Unified JSON log schema
- docs/log-schema.md

---

## 🔵 DAY 4 – Threat Modeling & MITRE ATT&CK Mapping

### Objectives
- Map anomalous behavior to MITRE ATT&CK techniques

### Deliverables
- docs/threat-model.md

---

## 🔵 DAY 5 – System Architecture Design

### Objectives
- Design end-to-end SOC-style pipeline

### Deliverables
- docs/architecture.md
- Architecture diagram

---

## 🔵 DAY 6 – Repository Initialization

### Objectives
- Create clean repository structure

### Deliverables
- ingestion-service/
- streaming/
- feature-engineering/
- ml-engine/
- alert-engine/
- backend-api/
- dashboard/
- docs/

---

## 🔵 DAY 7 – Log Ingestion Service

### Objectives
- Read Linux logs safely
- Handle large files and rotation

---

## 🔵 DAY 8 – Log Parsing Engine

### Objectives
- Parse logs into structured JSON
- Normalize timestamps

---

## 🔵 DAY 9 – Kafka Setup & Producers

### Objectives
- Stream logs in real time using Kafka

---

## 🔵 DAY 10 – Kafka Consumers

### Objectives
- Consume and process streaming events

---

## 🔵 DAY 11 – Feature Design

### Objectives
- Define behavioral and time-series features

---

## 🔵 DAY 12 – Feature Extraction Engine

### Objectives
- Implement feature calculations

---

## 🔵 DAY 13 – Data Cleaning & Validation

### Objectives
- Remove noise and inconsistencies

---

## 🔵 DAY 14 – Feature Pipeline Testing

### Objectives
- Validate feature correctness

---

## 🔵 DAY 15 – Phase 2 Review

### Objectives
- Ensure clean and reliable data pipeline

---

## 🔵 DAYS 16–28 – Machine Learning Engine

### Includes
- Isolation Forest training
- Autoencoder training
- Anomaly scoring
- Explainable AI
- Drift detection

---

## 🔵 DAYS 29–40 – Backend, Alerts & Dashboard

### Includes
- REST APIs
- JWT Authentication
- RBAC
- Alert engine
- Dashboard UI

---

## 🔵 DAYS 41–45 – Documentation & Public Release

### Includes
- Final documentation
- Architecture diagrams
- Demo scenarios
- Resume and LinkedIn content

---

## 📌 Disclaimer
This project is for educational and research purposes only.

---

## 👤 Author
**S M**  
Computer Science & Engineering  
Interests: AI Systems, Cybersecurity, Backend Engineering, OS Internals
