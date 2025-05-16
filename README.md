# 🏦 Kafka Banking App (.NET + Docker + Kubernetes)

A simple event-driven **Banking Application** demo that uses:
- **Apache Kafka** for message streaming
- **.NET Core** for Producer and Consumer services
- **Docker** for containerization
- **Kubernetes** for orchestration

---

## 📌 Project Overview

This application simulates basic banking operations using a Kafka-based event pipeline:

- `TransactionProducer`: Publishes banking events (e.g., deposits, withdrawals) to Kafka.
- `TransactionConsumer`: Subscribes to Kafka topics and processes transactions.
- Designed for local or cloud-based container orchestration using Kubernetes.

---

## 🚀 Tech Stack

| Component          | Technology             |
|-------------------|------------------------|
| Message Broker     | Apache Kafka           |
| Language & Runtime | .NET Core (6/7)        |
| Containerization   | Docker                 |
| Orchestration      | Kubernetes + YAML      |

