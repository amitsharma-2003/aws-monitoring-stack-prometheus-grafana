# 🚀 AWS Monitoring Stack using Prometheus, Grafana, Loki, Grafana Alloy & Alertmanager

A production-inspired monitoring and centralized logging solution built on **AWS EC2** using **Prometheus, Grafana, Loki, Grafana Alloy, Alertmanager, and Node Exporter**.

---

# 📖 Project Overview

This project demonstrates how to build a complete monitoring and centralized logging solution on AWS using open-source observability tools.

The monitoring stack collects infrastructure metrics from multiple Linux servers using **Node Exporter**, stores them in **Prometheus**, visualizes them in **Grafana**, collects logs using **Grafana Alloy**, stores logs in **Loki**, and sends email notifications using **Alertmanager** whenever predefined alert conditions are met.

The entire solution was deployed on **Amazon EC2** instances and follows production-inspired monitoring practices.

---

# 🛠️ Tech Stack

| Tool | Purpose |
|------|---------|
| AWS EC2 | Infrastructure |
| Ubuntu 24.04 LTS | Operating System |
| Prometheus | Metrics Collection |
| Node Exporter | Linux Metrics |
| Grafana | Visualization |
| Loki | Log Aggregation |
| Grafana Alloy | Log Collection |
| Alertmanager | Alert Routing |
| Gmail SMTP | Email Notifications |

---

# ✨ Features

- ✅ Infrastructure Monitoring
- ✅ CPU Monitoring
- ✅ Memory Monitoring
- ✅ Disk Monitoring
- ✅ Network Monitoring
- ✅ Centralized Logging
- ✅ Multi-Server Monitoring
- ✅ Email Alerts
- ✅ Grafana Dashboards
- ✅ Loki Log Exploration
- ✅ Production-Style Deployment

---

# ☁️ AWS Infrastructure

| Server | Purpose |
|---------|----------|
| Monitor Server | Prometheus, Grafana, Loki, Alertmanager |
| Server-1 | Node Exporter + Grafana Alloy |
| Server-2 | Node Exporter + Grafana Alloy |
