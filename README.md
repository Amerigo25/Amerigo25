## 👋 Amerigo Aloisi - AI Engineer


[![LinkedIn](https://img.shields.io/badge/LinkedIn-Amerigo%20Aloisi-0077B5?style=flat&logo=linkedin)](https://www.linkedin.com/in/amerigo-aloisi-b97a1213a/)
[![Email](https://img.shields.io/badge/Email-amerigo.aloisi%40gmail.com-D14836?style=flat&logo=gmail)](mailto:amerigo.aloisi@gmail.com)

---

## What I Build

I design and ship AI systems that run in production — multi-agent architectures, computer vision pipelines, and ML models at scale.

At **Liquid Reply**, I architected and deployed a production **multi-agent system** consisting of 2 orchestrator agents and 4 specialized sub-agents, built on **LangChain/LangGraph** and deployed as microservices on **OpenShift**. The system integrates 7 external services (OpenShift, Bitbucket, GCP, Azure, Dynatrace, Splunk, on-prem virtualizers) through async tool-calling APIs (`asyncio`/`httpx`), with **RAG-based memory** and full observability via **Langfuse**, **Grafana**, and **Splunk**.

At **Sony Stuttgart**, my research on **Vision Transformer (ViT)** models for hyperspectral image classification — trained on multi-GPU clusters via **Slurm** — resulted in a **granted European patent**:

> 📄 *"Image Processing Device, Waste Sorting System, and Corresponding Methods and Computer Programs"* — EPO, 2026

---

## Core Areas

| Domain | What I've Actually Done |
|---|---|
| **Multi-Agent Systems** | Production orchestrator + sub-agent architecture, async tool-calling, RAG memory, LangGraph state management |
| **LLM Infrastructure** | Microservice deployment on OpenShift, observability with Langfuse/Grafana/Splunk, multi-service integration |
| **Computer Vision** | ViT training for hyperspectral classification, SIFT-based autoencoder for Structure from Motion, OpenCV pipelines |
| **ML at Scale** | Multi-GPU training via Slurm, PyTorch/TensorFlow model development, research-to-production workflows |

---

## Selected Project

### SIFT Autoencoder for Structure from Motion
*Python · Keras · OpenCV · COLMAP*

Designed an autoencoder architecture to learn compressed SIFT feature representations for use in Structure from Motion pipelines. Combined classical geometric methods with learned feature embeddings.

---

## Tech Stack

```
LLM / Agents     LangChain · LangGraph · Haystack · Langfuse
ML / CV          PyTorch · TensorFlow · OpenCV
Infrastructure   Docker · Kubernetes · OpenShift · Slurm · Jenkins
Observability    Grafana · Splunk
Databases        PostgreSQL · MySQL
Languages        Python · C++
```
