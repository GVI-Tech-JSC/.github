<div align="center">

# GVI Tech JSC

**Building the gGVI Network (VNKR) — Vietnam's DeFi Protocol & App-Chain**

[![Website](https://img.shields.io/badge/Website-vnkr.vn-3b82d4?style=flat-square)](https://vnkr.vn)
[![Chain ID](https://img.shields.io/badge/EVM_Chain_ID-78968-7c5cd8?style=flat-square)](https://rpc.vnkr.vn)
[![Repos](https://img.shields.io/badge/Repositories-55-green?style=flat-square)](https://github.com/orgs/GVI-Tech-JSC/repositories)
[![License](https://img.shields.io/badge/License-AGPL--3.0-orange?style=flat-square)](https://www.gnu.org/licenses/agpl-3.0.en.html)

</div>

---

## 🏗️ About GVI Tech JSC

**GVI Tech JSC** is the technology arm of the **gGVI Group** — a Vietnamese Web3 conglomerate building a full-stack DeFi ecosystem on the **VNKR Network**, an EVM-compatible app-chain.

We maintain open-source protocol contracts, frontend dApps, and infrastructure for four group entities:

| Entity | Focus |
|---|---|
| 🏛 **Tech Holding JSC** | Core protocol, smart contracts, DevOps & governance |
| 💹 **Financial & Trading JSC** | Treasury, bonds, liquidity & Range Bound Stability |
| 💳 **Payment & Commerce JSC** | VNKR payment rail, KYC/eKYC, e-commerce gateway |
| 🎮 **Entertainment & Web3 JSC** | NFTs, gaming, metaverse & community |

---

## ⛓️ VNKR Network

| Parameter | Value |
|---|---|
| Chain ID | `78968` |
| Native Currency | `GVI` |
| Pegged Currency | `VNKR` |
| RPC | `https://rpc.vnkr.vn` |
| WebSocket | `wss://ws.vnkr.vn` |
| Block Explorer | `https://scan.vnkr.vn` |
| Consensus | Clique PoA |

---

## 📦 Core Repositories

### 🔐 Smart Contracts
| Repo | Description |
|---|---|
| [`gGVI-Monorepo`](https://github.com/GVI-Tech-JSC/gGVI-Monorepo) | Full monorepo — GVI Token, sGVI, gGVI, Staking, Treasury, Vesting, P2P Escrow |
| [`gvi-contracts-v2`](https://github.com/GVI-Tech-JSC/gvi-contracts-v2) | Advanced protocol mechanics (Hardhat/Solidity) |
| [`ggvi-v3`](https://github.com/GVI-Tech-JSC/ggvi-v3) | gGVI Protocol v3 with cross-chain features |
| [`forge-proposal-simulator`](https://github.com/GVI-Tech-JSC/forge-proposal-simulator) | On-chain governance proposal testing (Foundry) |

### 🌐 Frontend & dApps
| Repo | Description |
|---|---|
| [`gvi-frontend`](https://github.com/GVI-Tech-JSC/gvi-frontend) | Main dApp — staking, treasury, governance (React/Vite) |
| [`gvi-docs`](https://github.com/GVI-Tech-JSC/gvi-docs) | Protocol documentation (Docusaurus) |
| [`emergency-frontend`](https://github.com/GVI-Tech-JSC/emergency-frontend) | Fallback UI for critical protocol actions |

### 📊 Data & Subgraphs
| Repo | Description |
|---|---|
| [`gvi-subgraph`](https://github.com/GVI-Tech-JSC/gvi-subgraph) | Core protocol event indexer (The Graph) |
| [`treasury-subgraph`](https://github.com/GVI-Tech-JSC/treasury-subgraph) | Treasury asset & flow indexer |
| [`protocol-metrics-subgraph-gvi`](https://github.com/GVI-Tech-JSC/protocol-metrics-subgraph-gvi) | Protocol KPIs & analytics |
| [`gvi-price-subgraph`](https://github.com/GVI-Tech-JSC/gvi-price-subgraph) | Real-time GVI/VNKR price feeds |

---

## 🏛️ Governance

GVI Network uses **3-of-5 Gnosis Safe multi-sig** with on-chain governance via `GVIGovernor` + `GVITimelock`:

```
Proposal → Voting (72h) → Timelock (48h) → Execution
```

- Governance token: `GVI` (weight via `gGVI` wrapping)
- Quorum: 4% of circulating supply
- Proposal threshold: 1,000 GVI

---

## 🤝 Contributing

We welcome community contributions!

1. Read the [Contributing Guide](https://github.com/GVI-Tech-JSC/.github/blob/main/CONTRIBUTING.md)
2. Fork and create a feature branch: `feat/your-feature`
3. Ensure `pnpm test` and `pnpm lint` pass
4. Submit a Pull Request — CI must pass before review

---

## 🔐 Security

To report a vulnerability: **security@vnkr.vn** or open a [Security Advisory](https://github.com/GVI-Tech-JSC/gGVI-Monorepo/security/advisories/new).

**Never open a public issue for security vulnerabilities.**

---

## 📄 License

All GVI-originated code: **[AGPL-3.0](https://www.gnu.org/licenses/agpl-3.0.en.html)** · Third-party packages retain original licenses.

---

<div align="center">
<sub>© 2025 GVI Tech JSC · Ho Chi Minh City, Vietnam · <a href="https://vnkr.vn">vnkr.vn</a></sub>
</div>
