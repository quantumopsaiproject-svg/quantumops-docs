# QuantumOps AI – System Architecture

## Components
- **QuantumOps-Agent** (runs on validator nodes)
- **QuantumOps-Core** (backend API)
- **QuantumOps-Dashboard** (frontend)
- **PostgreSQL** (metrics & metadata)
- **MongoDB** (logs & events)
- **AI Module** (LLM interface)
- **Automation Engine**

## Data Flow
1. Agent collects system + validator data
2. Sends JSON payload to Core
3. Core stores metrics in PostgreSQL
4. Logs stored in MongoDB
5. Dashboard reads from Core
6. AI module explains errors
7. Automation triggers actions

## Target Networks
- Phase 1: Cosmos ecosystem (FET testnet)
- Phase 2: All Cosmos SDK chains
- Phase 3: Other PoS networks