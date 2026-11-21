# GenLayer Intelligent Contracts

Two Intelligent Contracts for GenLayer. Each one lives in its own repository with
its own unit, integration and adversarial test suites, CI, and a committed
deployment record. This repository is only the index.

| Contract | Repository | Deployed on studionet |
|---|---|---|
| `FreelanceEscrow` | [genlayer-freelance-escrow](https://github.com/rizqhika29/genlayer-freelance-escrow) | `0xceCb2f0867ffB07bB400605321BF9d839a12c9EF` |
| `PredictionMarket` | [genlayer-prediction-market](https://github.com/rizqhika29/genlayer-prediction-market) | `0xCF2AAe90a182f0a37C047c57C6a0FD67D9AaF9c0` |

Both contracts deploy from the same wallet
(`0xABa75FaB2Fa28B176C48aD99aeB833C09A5e15B9`) and use the same dependency header:

```py
# { "Depends": "py-genlayer:1jb45aa8ynh2a9c9xn3b7qqh8sm5q93hwfp7jqmwsfhh8jpz09h6" }
```

The full deployment evidence (address, deployer, chain id 61999, timestamp,
source sha256 and the deploy receipt) is committed in each repository under
`deployments/`.

This repository used to hold both contracts before the split. The old code,
tests and workflow are still in its git history but are no longer used; archive
or delete it on GitHub if you prefer.
