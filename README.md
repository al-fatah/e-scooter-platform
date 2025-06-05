# 🛴 E-Scooter Platform PoC

This project is a proof-of-concept (PoC) for a scalable, extensible, and maintainable e-scooter sharing platform designed for multi-country deployments. It demonstrates microservices architecture, cloud-native tooling, and real-time ride operations.

---

## 📌 Project Objectives

- Validate a cloud-native, modular architecture
- Simulate core ride and payment workflows
- Demonstrate scalability and extensibility
- Enable observability and DevOps practices

---

## 🧱 Architecture Overview

- **Frontend:** React Native (Mobile App), React.js (Admin Dashboard)
- **Backend:** Microservices (Node.js or Python), REST APIs, JWT Auth
- **Cloud Infrastructure:** Kubernetes, API Gateway, CI/CD, Prometheus
- **Data Stores:** PostgreSQL, NoSQL (DynamoDB/Firestore), S3-compatible storage

---

## 🧰 Tech Stack

| Layer         | Technology                    |
|---------------|-------------------------------|
| Frontend      | React Native, React.js        |
| Backend       | FastAPI / Node.js (Express)   |
| Infrastructure| Kubernetes, Helm, Terraform   |
| CI/CD         | GitHub Actions / GitLab CI    |
| Auth          | OAuth2 / JWT                  |
| Monitoring    | Prometheus, Grafana, Loki     |
| Database      | PostgreSQL, DynamoDB          |
| Payments      | Stripe (Test Mode)            |

---

## 📂 Folder Structure

```bash
e-scooter-platform-poc/
├── frontend/
│   ├── mobile-app/          # React Native App
│   └── admin-portal/        # Admin Dashboard
├── services/
│   ├── user-service/        # Auth, Registration
│   ├── ride-service/        # Ride lifecycle
│   ├── telemetry-service/   # Vehicle location + battery
│   ├── payment-service/     # Stripe integration
│   └── notification-service/# Push/Email alerts
├── infra/                   # Terraform + Helm configs
├── shared/                  # Common utils + auth modules
├── .github/                 # CI/CD workflows
└── docs/                    # Architecture, API specs
