# API Design – QuantumOps Core

## Endpoints

### Agent → Backend
- POST /metrics
- POST /logs
- POST /heartbeat

### Backend → Dashboard
- GET /nodes
- GET /nodes/{id}
- GET /alerts
- GET /ai/analysis

### Automation
- POST /actions/restart
- POST /actions/reset-peers