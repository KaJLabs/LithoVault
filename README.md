![Coverage](https://codecov.io/gh/KaJLabs/LithoVault/branch/main/graph/badge.svg)
![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Network](https://img.shields.io/badge/network-Lithosphere%20Makalu-purple)
![Chain ID](https://img.shields.io/badge/chain--id-700777-green)
![Status](https://img.shields.io/badge/status-beta-orange)

# 🚀 LithoVault

Autonomous AI-powered treasury infrastructure built on Lithosphere

---

## 🧠 Overview

LithoVault is a production-grade autonomous treasury system that enables enterprises and individuals to manage capital using AI-driven DeFi strategies.

Built on the **Lithosphere network**, the platform combines:

- AI agents (Quantts)
- APP payment rails
- DNNS identity layer
- MultX execution coordination
- Multi-signature governance

---

## ⚙️ Core Features

- 🤖 Autonomous treasury execution via AI agents
- 💸 Multi-protocol DeFi strategy orchestration
- 🛡️ Enterprise-grade governance (multi-sig + policy controls)
- 📊 Real-time analytics (PnL, risk, exposure)
- 🔗 Cross-chain ready execution via MultX
- 🧾 Immutable audit trails for compliance

---

## 🧩 Tech Stack

### On-Chain

- Lithosphere (Makalu Testnet)
- Lithic smart contracts
- EVM-compatible integrations

### Off-Chain

- Node.js (API + agent orchestration)
- Next.js (web dashboard)
- React Native (mobile apps)
- PostgreSQL + Redis
- Kafka / queue systems

### AI Layer

- Multi-model orchestration (LLMs)
- Strategy execution pipelines
- Risk and optimization engines

---

## 🌐 Network Configuration

- **Network Name:** Lithosphere Makalu
- **Chain ID:** 700777
- **RPC URL:** https://rpc.litho.ai
- **Explorer:** https://explorer.litho.ai

---

## 📦 Monorepo Structure

```bash
.
├── apps/
│   ├── web/        # Next.js dashboard
│   ├── mobile/     # React Native app
│   └── admin/      # Governance UI
│
├── backend/
│   ├── api/        # Backend services
│   ├── agents/     # AI agent runtime
│   ├── execution/  # MultX + APP integration
│   ├── indexer/    # Blockchain indexer
│   └── analytics/  # Risk + PnL engine
│
├── contracts/
│   ├── lithic/     # Core contracts
│   └── integrations/
│
├── sdk/
│   ├── js/
│   ├── python/
│   └── rust/
│
├── cli/
│   └── lithovault-cli
│
├── docs/
│   ├── whitepaper/
│   ├── api/
│   └── sdk/
│
└── infra/
    ├── docker/
    ├── k8s/
    └── terraform/
```

---

## 🚀 Quick Start

### 1. Clone Repo

```bash
git clone https://github.com/your-org/lithovault.git
cd lithovault
```

### 2. Install Dependencies

```bash
pnpm install
# or
yarn install
```

### 3. Setup Environment

```bash
cp .env.example .env
```

Update:

```env
RPC_URL=https://rpc.litho.ai
CHAIN_ID=700777

PRIVATE_KEY=your_private_key
DATABASE_URL=postgres://...
REDIS_URL=redis://...

MULTX_ENDPOINT=https://multx.litho.ai
DNNS_ENDPOINT=https://dnns.litho.ai
```

### 4. Run Backend

```bash
cd backend/api
pnpm dev
```

### 5. Run Web App

```bash
cd apps/web
pnpm dev
```

### 6. Start Agents

```bash
cd backend/agents
pnpm start
```

---

## 🧠 CLI Usage

```bash
lithovault init
lithovault deploy-vault
lithovault deposit
lithovault rebalance
lithovault agents start
```

---

## 📡 API Example

```http
POST /vault/rebalance
```

```json
{
  "vaultId": "0x123...",
  "strategy": "yield-optimizer"
}
```

---

## 🧱 Smart Contracts

### Core Modules

- Vault (asset management)
- Strategy Manager (execution logic)
- Risk Module (limits + circuit breakers)
- Governance (multi-sig + proposals)
- DNNS Registry (identity)
- ZK Identity Verifier

---

## 🤖 Agent System

| Agent Type        | Function               |
|------------------|------------------------|
| Yield Agent      | Maximizes returns      |
| Risk Agent       | Monitors exposure      |
| Rebalance Agent  | Maintains allocations  |
| Governance Agent | Executes approvals     |

---

## 🔄 Execution Flow

```
AI Decision
  ↓
APP Payment Intent
  ↓
MultX Execution
  ↓
Smart Contract Call
  ↓
Settlement on Lithosphere
```

---

## 🔐 Security

- Multi-signature governance
- Transaction simulation before execution
- Circuit breakers for risk events
- Role-based access control
- Audit logging for all actions

---

## 🧪 Development Flags

```env
AI_MODE=mock
DRY_RUN=true
DEBUG=true
FORK_MODE=true
```

---

## 🧱 Deployment

### Docker

```bash
docker-compose up --build
```

### Kubernetes

```bash
kubectl apply -f infra/k8s/
```

---

## 📊 Monitoring

- Prometheus metrics
- Grafana dashboards
- OpenTelemetry tracing
- Real-time alerting

---

## 🧾 Whitepaper

Available in:

```
docs/whitepaper/
```

Includes:

- Protocol architecture
- AI execution model
- Risk framework
- Economic design

---

## 🔗 Integrations

- Lithosphere Network
- DNNS Identity Layer
- APP Protocol (payments)
- MultX (execution coordination)
- DeFi protocols (staking, LPs, stablecoins)

---

## 🛣️ Roadmap

- Core vault architecture
- AI agent system
- Makalu testnet deployment
- Cross-chain treasury bridge
- zk-identity layer (production)
- Mainnet deployment
- Institutional onboarding

---

## 🤝 Contributing

fork → branch → commit → PR

Please follow:

- Conventional commits
- Code linting rules
- Test coverage requirements

---

## 📜 License

MIT License

---

## ⚠️ Disclaimer

This software is experimental and intended for development and testing. Use at your own risk. Smart contracts and AI systems are subject to failure.

---

## 🌍 Links

- 🌐 Project: https://lithovault.ai
- 🌐 Explorer: https://explorer.litho.ai
- 🔗 RPC: https://rpc.litho.ai
- 🧠 DNNS: https://dnns.litho.ai
- ⚡ MultX: https://multx.litho.ai

