# KURA

**KURA** is a hybrid decentralized cloud storage platform designed to securely upload, store, and distribute files by combining centralized cloud infrastructure with decentralized storage networks.

KURA provides a unified API that abstracts the underlying storage layer, allowing files to be stored on centralized object storage, decentralized networks, or both.

##  Features
- Secure file uploads via presigned URLs
- Hybrid storage strategy (centralized + decentralized)
- Centralized object storage with Amazon S3
- Decentralized content-addressed storage with IPFS
- No cloud credentials exposed to the frontend
- High-performance and memory-safe backend written in Rust
- Fully containerized services
- Cloud-native and scalable architecture

## Architecture

Frontend
↓
KURA API (Rust / Axum)
↓
Storage Abstraction
├── Amazon S3 (centralized)
├── IPFS (decentralized)
└── Hybrid (S3 + IPFS)

## Tech Stack

### Frontend
- React
- Vite
- TypeScript

### Backend
- Rust
- Axum (HTTP API)
- Tokio (async runtime)
- Serde (serialization)
- AWS SDK for Rust (S3)
- IPFS HTTP API (decentralized storage)

### Infrastructure
- Amazon S3 (object storage)
- IPFS (content-addressed storage)
- Docker (containerization)
- AWS (cloud provider)

---

## 🚀 Getting Started
*(Coming soon)*
