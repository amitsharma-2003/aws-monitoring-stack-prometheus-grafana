AWS Monitoring Stack using Prometheus, Grafana, Loki, Grafana Alloy & Alertmanager
Project Overview

This project demonstrates how to build a complete monitoring and centralized logging solution on AWS using open-source observability tools.

The monitoring stack collects infrastructure metrics from multiple Linux servers using Node Exporter, stores them in Prometheus, visualizes them in Grafana, collects logs using Grafana Alloy, stores logs in Loki, and sends email notifications using Alertmanager whenever predefined alert conditions are met.

The entire solution was deployed on Amazon EC2 instances and follows production-inspired monitoring practices.

Project Architecture
                +----------------------+
                |     Server-1         |
                |----------------------|
                | Node Exporter        |
                | Grafana Alloy        |
                +----------+-----------+
                           |
                           |
                           |
                +----------v-----------+
                |                      |
                |    Monitor Server    |
                |----------------------|
                | Prometheus           |
                | Grafana              |
                | Loki                 |
                | Alertmanager         |
                +----------^-----------+
                           |
                           |
                +----------+-----------+
                |     Server-2         |
                |----------------------|
                | Node Exporter        |
                | Grafana Alloy        |
                +----------------------+
Tech Stack
Tool	Purpose
AWS EC2	Infrastructure
Ubuntu 24.04	Operating System
Prometheus	Metrics Collection
Node Exporter	Linux Metrics
Grafana	Visualization
Loki	Log Aggregation
Grafana Alloy	Log Collection
Alertmanager	Alert Routing
Gmail SMTP	Email Notifications
Features

✔ Infrastructure Monitoring

✔ CPU Monitoring

✔ Memory Monitoring

✔ Disk Monitoring

✔ Network Monitoring

✔ Centralized Logging

✔ Multi-Server Monitoring

✔ Email Alerts

✔ Grafana Dashboards

✔ Loki Log Exploration

✔ Production-style Architecture

AWS Infrastructure
Server	Purpose
Monitor Server	Prometheus, Grafana, Loki, Alertmanager
Server-1	Node Exporter + Grafana Alloy
Server-2	Node Exporter + Grafana Alloy
Monitoring Workflow
Linux Server
      │
      ▼
Node Exporter
      │
      ▼
Prometheus
      │
      ▼
Grafana Dashboard
Logging Workflow
Linux Logs

      │

      ▼

Grafana Alloy

      │

      ▼

Loki

      │

      ▼

Grafana Explore
Alerting Workflow
Node Exporter

      │

      ▼

Prometheus Alert Rules

      │

      ▼

Alertmanager

      │

      ▼

Email Notification
Project Screenshots

Screenshots are available in the screenshots directory.

Folder Structure
aws-monitoring-stack-prometheus-grafana/

├── README.md
├── architecture/
├── configs/
├── docs/
├── screenshots/
└── assets/
Future Improvements
Kubernetes Monitoring
Blackbox Exporter
SSL/TLS
Grafana Dashboard Provisioning
Docker Deployment
Terraform Automation
Ansible Automation
Author

Amit Sharma
