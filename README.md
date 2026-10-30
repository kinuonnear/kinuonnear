# KINU

The DeFi Hub on NEAR: swap, provide liquidity on Rhea, bridge and earn, every action signed in your own wallet.

[Website](https://kinudefi.com) · [Docs](https://kinudefi.com/docs) · [Security](https://kinudefi.com/security) · [X](https://x.com/KINUonNEAR)

### Products

| Name | What it does | Source |
| --- | --- | --- |
| [Swap](https://kinudefi.com) | Best route across Rhea and the Intear DEX aggregator | Closed |
| [Pools](https://kinudefi.com/pools) | Rhea DCL and classic pools: create, zap in, rebalance, PnL and fee history | Closed |
| [LP Guardian](https://kinudefi.com/guardian) | An agent in an OutLayer TEE keeps your Rhea position in range, only within rules the contract enforces | [kinu-lp-guardian](https://github.com/kinuonnear/kinu-lp-guardian) (contract + agent) |
| [Earn](https://kinudefi.com/earn) | Rhea Lend, plus yield on other chains through NEAR Intents | Closed |
| [Bridge](https://kinudefi.com/bridge) | Deposit, withdraw and swap across chains with NEAR Intents | Closed |
| [Telegram bot](https://t.me/Kinu_LPbot) | Quick LP from Telegram: pick a pool and range, then sign in your own wallet | Closed |

### How we handle trust

- Code that holds user funds is open source and built reproducibly, so the deployed code hash can be checked: [kinu-lp-guardian](https://github.com/kinuonnear/kinu-lp-guardian).
- The web app never holds funds: every transaction is checked in the browser before your wallet sees it, and you sign it yourself.
- Internal security reviews and their findings are published on [kinudefi.com/security](https://kinudefi.com/security).
