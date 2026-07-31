# Contributing to GVI Tech JSC

Thank you for your interest in contributing to the gGVI Network!

## Development Setup

```bash
git clone https://github.com/GVI-Tech-JSC/gGVI-Monorepo.git
cd gGVI-Monorepo
pnpm install
cp .env.example .env   # fill in VNKR_RPC_URL, DEPLOYER_KEY, etc.
pnpm test
```

## Branching Strategy

| Branch | Purpose |
|---|---|
| `main` | Protected — merges only from `release/*` or `hotfix/*` |
| `develop` | Integration — all PRs target here |
| `feat/*` | New features |
| `fix/*` | Bug fixes |
| `chore/*` | Maintenance, deps, config |
| `docs/*` | Documentation only |
| `hotfix/*` | Critical production fixes |

## Pull Request Checklist

- [ ] `pnpm test` passes locally
- [ ] `pnpm lint` passes with no new warnings
- [ ] New contracts have 100% coverage on critical paths
- [ ] Solidity changes include NatSpec documentation
- [ ] Breaking changes documented in `CHANGELOG.md`
- [ ] PR references the related Issue (`Closes #123`)

## Commit Messages (Conventional Commits)

```
<type>(scope): <short description>
```

Types: `feat` | `fix` | `docs` | `chore` | `refactor` | `test` | `ci` | `perf`

Examples:
```
feat(staking): add auto-compound for sGVI holders
fix(treasury): correct bond price oracle overflow
chore(deps): upgrade hardhat to v2.22.0
```

## Smart Contract Guidelines

- All mainnet contracts MUST be audited before deployment
- Target Solidity `^0.8.20`
- Follow Checks-Effects-Interactions pattern
- No floating pragmas in production contracts
- Run `forge test` + `hardhat test` for dual coverage

## Review Process

1. CI (lint + tests + typecheck) must pass
2. Minimum 1 review from `@GVI-Tech-JSC/core-devs`
3. Smart contract changes require 2 reviews
4. Final merge by repository maintainer

## License

By contributing, you agree that your contributions will be licensed under **AGPL-3.0**.
