# Security Policy — GVI Tech JSC

## Supported Versions

| Version | Supported |
|---|---|
| gGVI Monorepo `main` | ✅ Active |
| gvi-contracts-v2 `main` | ✅ Active |
| ggvi-v3 `main` | ✅ Active |
| gvi-contracts-v1 | ⚠️ Critical fixes only |

## Reporting a Vulnerability

**DO NOT open a public GitHub Issue for security vulnerabilities.**

### Preferred — Private Security Advisory
Open a [GitHub Security Advisory](https://github.com/GVI-Tech-JSC/gGVI-Monorepo/security/advisories/new) on the affected repository.

### Email
Send a detailed report to **security@vnkr.vn** with:
- Affected repository and version
- Proof of concept or reproduction steps
- Potential impact assessment
- Suggested fix (optional)

## Response Timeline

| Stage | SLA |
|---|---|
| Initial acknowledgment | 24 hours |
| Severity assessment | 72 hours |
| Patch development | 7–30 days (severity-dependent) |
| Public disclosure | 90 days after patch release |

## Scope

**In-scope:**
- Smart contracts on VNKR Network (Chain ID: 78968)
- Frontend dApps at `*.vnkr.vn`
- GVI SDK (`gvi-sdk`)
- On-chain governance contracts (`GVIGovernor`, `GVITimelock`)

**Out-of-scope:**
- Third-party integrations (Gnosis Safe, The Graph)
- Testnet deployments
- Social engineering / phishing attacks

## Bug Bounty

Critical vulnerabilities affecting mainnet contracts may be eligible for bounty rewards.
Contact **security@vnkr.vn** for eligibility details.
