# Invero 📦

**Real-time Inventory and Supply Chain Monitoring System**

Invero is an open-source, real-time inventory and supply chain monitoring solution built for speed, intelligence, and global visibility. Designed with modern technology stacks, Invero ensures your supply chain operations are resilient, transparent, and highly efficient.

## 🚀 Features

- **Real-time Inventory Tracking**
- **Shipment Monitoring & Location Intelligence**
- **Supply Chain Risk Management**
- **Predictive Analytics and Demand Forecasting**
- **AI-Powered Anomaly Detection**
- **Blockchain-based Traceability**
- **Digital Twin Supply Chain Simulation**
- **Executive Dashboards and KPIs**
- **Multi-channel Alerts (Email, SMS, Push)**
- **IoT & ERP Integration Ready**

## 🛠 Tech Stack

- **Backend**: Rust 🦀 + SeaORM + PostgreSQL 🐘
- **Containerization**: Docker 🐳 (Primary Deployment)
- **Frontend**: Next.js + Tailwind CSS
- **Messaging**: MQTT, WebSockets
- **External Integrations**: SAP, Oracle NetSuite, Weather APIs, Logistics APIs

## 📦 Project Structure

```
/novex
 ├── backend/ (Rust services)
 ├── frontend/ (Next.js dashboard)
 ├── docker-compose.yml (Main orchestration)
 ├── docs/ (Project documentation)
 └── README.md
```

## 🚢 Quickstart

### Requirements

- Docker & Docker Compose installed
- Rust toolchain (if you want to develop backend locally)
- Node.js 18+ (for frontend development)

### Running with Docker

```bash
git clone https://github.com/your-org/novex.git
cd novex
docker-compose up --build
```

Access the dashboard at [http://localhost:3000](http://localhost:3000).


### Running Locally (Dev Mode)

1. **Backend**

```bash
cd backend
cp .env.example .env
cargo run
```

2. **Frontend**

```bash
cd frontend
cp .env.local.example .env.local
npm install
npm run dev
```

Access dashboard: [http://localhost:3000](http://localhost:3000)


## 🧩 Architecture Overview

```
[IoT Devices / ERP Systems / External APIs]
       ↓
API Gateway → Message Queue → Rust Core Services (Inventory, Supply Chain, Analytics)
       ↓
Databases (PostgreSQL + Caching Layer)
       ↓
GraphQL API + WebSocket Server
       ↓
Next.js Frontend (Server Components)
```


## 📚 Documentation

- [Overview](./docs/overview.md)
- [API Reference](./docs/api.md)
- [System Design](./docs/design.md)
- [Deployment Guide](./docs/deployment.md)


## 🙌 Contributing

We ❤️ contributions!

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

Read our full [Contributing Guide](./CONTRIBUTING.md).


## 📄 License

This project is licensed under the MIT License. See the [LICENSE](./LICENSE) file for details.


## 💬 Community and Support

- [Discussions](https://github.com/your-org/novex/discussions)
- [Issues](https://github.com/your-org/novex/issues)
- [Feature Requests](https://github.com/your-org/novex/issues/new?template=feature_request.md)

---

Made with ❤️ by the Invero Community.
