# SimulateN Documentation

Welcome to the official documentation for **SimulateN** — the AI-powered contact center simulation engine built for rapid planning, forecasting, and operational testing.

This repository contains both **product documentation** and **developer-facing API references** for SimulateN.

---

## 🚀 Product Overview

SimulateN helps contact center leaders plan with confidence by simulating real-world operations across demand, staffing, channels, and customer experience.

### 🔧 Core Capabilities

| Feature | Description |
|--------|-------------|
| **Contact Volume Simulation** | Simulate inbound contact patterns over time across voice, chat, email, and more. |
| **Self-Service Containment Modeling** | Define and test containment assumptions across IVR, chatbots, and automation layers. |
| **Routing & Handling Simulation** | Emulate queueing behavior, agent routing, and handling times by channel and skill. |
| **Forecasting Experiments** | Benchmark traditional vs. AI-based forecasting models and assess accuracy. |
| **What-If Scenarios** | Model staffing plans, outages, or channel mix shifts using scenario branches. |

---

## 📡 API Documentation

SimulateN exposes a RESTful API to allow integration, automation, and simulation control. Below are the available API sets:

### 🔐 Authentication & Identity

- `POST /signup` — Create a new user account
- `POST /auth` — Retrieve access token
- `GET /me` — Get current user details

### 🏢 Organizations & Teams

- `POST /organizations` — Create a new organization (tenant)
- `POST /teams` — Create a team under an org
- `POST /team-members` — Assign user to team with role

### 📊 Simulation Modules

- `POST /contact-generator` — Create or import contact volume profiles
- `POST /containment` — Define containment assumptions
- `POST /routing-sim` — Run routing/handling simulation
- `POST /forecast` — Execute model-based forecasting
- `POST /scenarios` — Create and compare simulation branches

*Interactive Swagger UI available at: [`/docs`](https://simulate-api.yourdomain.com/docs)*

---

## 📚 Get Started

To get started with SimulateN:

1. Sign up for an account at [simulate.app](https://simulate.app)
2. Read through our [Getting Started Guide](./docs/getting-started.md)
3. Explore the [Public API Docs](./docs/api-overview.md)
4. Try our CLI or SDKs (coming soon)

---

## 🌐 Live Documentation

This repo is deployed at **[docs.simulaten.com](https://docs.simulaten.com)** — updated on every push to `main`.

---

## 🛠️ Contributing

We're not currently accepting external contributions. For internal collaboration, please use the private `simulate-internal-docs` repository.

---

## 📬 Contact

For enterprise licensing or support, reach out at [hello@simulaten.com](mailto:hello@simulaten.com)
