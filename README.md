# HealOps: Self-Healing Infrastructure Platform

A platform that monitors a microservices application, detects failures,
and automatically remediates them (restart, scale, rollback) with safety guardrails.

## Status
Under development: see [CHANGELOG.md](CHANGELOG.md) for current version.

## Planned Architecture
Demo microservices -> Prometheus/Grafana -> Incident manager -> Policy engine
-> Remediation workers -> Orchestrator (Docker / Kubernetes / AWS)

## Quick Start
Coming in v1.0.0 (`make up`).

## Repository Layout
| Folder | Purpose |
|---|---|
| `apps/` | Demo microservices (the system being protected) |
| `platform/` | Control plane: API, policy engine, remediation workers |
| `dashboard/` | Web UI |
| `ml/` | Anomaly detection service |
| `chaos/` | Failure-injection scripts |
| `observability/` | Prometheus, Grafana, Alertmanager configs |
| `k8s/` | Kubernetes manifests |
| `infra/` | Terraform (AWS deployment) |
| `docs/` | Architecture, decisions, learning log, results |
EOFcat > README.md << 'EOF'
# HealOps: Self-Healing Infrastructure Platform

A platform that monitors a microservices application, detects failures,
and automatically remediates them (restart, scale, rollback) with safety guardrails.

## Status
Under development: see [CHANGELOG.md](CHANGELOG.md) for current version.

## Planned Architecture
Demo microservices -> Prometheus/Grafana -> Incident manager -> Policy engine
-> Remediation workers -> Orchestrator (Docker / Kubernetes / AWS)

## Quick Start
Coming in v1.0.0 (`make up`).

## Repository Layout
| Folder | Purpose |
|---|---|
| `apps/` | Demo microservices (the system being protected) |
| `platform/` | Control plane: API, policy engine, remediation workers |
| `dashboard/` | Web UI |
| `ml/` | Anomaly detection service |
| `chaos/` | Failure-injection scripts |
| `observability/` | Prometheus, Grafana, Alertmanager configs |
| `k8s/` | Kubernetes manifests |
| `infra/` | Terraform (AWS deployment) |
| `docs/` | Architecture, decisions, learning log, results |
