# GitOps-Monitoring-Stack-with-Argo-CD-Helm-Kubernetes
GitOps Monitoring Stack with Argo CD, Helm &amp; Kubernetes


# GitOps Monitoring Stack with Argo CD, Helm & Kubernetes

This project demonstrates a **GitOps-based Kubernetes setup** using **Argo CD** to deploy and manage applications via **Helm charts**, along with a complete **monitoring stack** using **Prometheus** and **Grafana**.

The goal is to showcase **real-world DevOps practices**:
- Declarative infrastructure
- GitOps workflows
- Automated sync & self-healing
- Kubernetes observability

---

## 🧱 Architecture Overview

- Argo CD manages application deployments using Git as the source of truth
- Helm charts are deployed via Argo CD Applications
- Prometheus scrapes Kubernetes and workload metrics
- Grafana visualizes cluster, node, and deployment metrics
- NGINX is used as a sample workload to generate metrics

---

## 📦 Components Used

- Kubernetes
- Argo CD
- Helm
- Prometheus (kube-prometheus-stack)
- Grafana
- NGINX

---

## 📁 Repository Structure

```text
gitops/
├── apps/
│   ├── prometheus.yaml
│   ├── grafana.yaml
│   └── nginx.yaml
└── README.md
