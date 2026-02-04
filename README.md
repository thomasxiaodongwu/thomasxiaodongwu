# Thomas Wu — Senior Blockchain / Backend Engineer (Remote · GMT+8)

I build production-grade **on-chain protocols** and **high-concurrency, low-latency off-chain systems** across Solana, Sui, and EVM.
Most of my work sits at the intersection of **DeFi perps/AMMs**, **NFT infrastructure**, **MEV/arbitrage execution**, and **data indexing/analytics**.

**Current focus**
- Solana perpetuals: risk/margin/liquidation, swap settlement, liquidity vaults & pool economics, keeper-based execution
- Sui/Solana NFT protocols: AMM / lottery / launchpad mechanics, royalty handling, gas/storage optimizations
- Web3 backend: wallet/key management, multi-chain routing, DEX aggregation, event-driven pipelines (Kafka/Redis/Postgres)

---

## What I’m good at

### Protocol engineering (on-chain)
- **Solana (Rust/Anchor)**: AMM & liquidity pool models, oracle integration & validation, perps settlement paths, keeper execution flows
- **EVM (Solidity)**: liquidation/arbitrage strategy wiring, pool-state tracking, event-driven execution
- **Sui (Move)**: resource-oriented contract design, minting/launchpad flows, refund/cap mechanisms

### Systems engineering (off-chain)
- Low-latency execution engines (keepers/bots), robust retry/failover patterns, cost-aware execution strategies
- High-throughput indexing & analytics: plugin/event capture → Redis/Kafka → PostgreSQL/Mongo → batch analytics (Databricks)
- Microservices & infra: Docker/K8s, AWS, observability, reliability under high concurrency

---

## Experience highlights (selected)

### GMX Limited — Senior Protocol Engineer (GMX-Solana Core)
- Worked on a **pool-based perpetual futures model** on Solana: market state, PnL tracking, liquidation/risk modules
- Built and hardened **oracle aggregation & validation** (freshness, deviation windows, expiry checks) to reduce bad-price execution risk
- Implemented parts of the **swap/settlement stack** to support cross-collateral conversions during open/close/add-margin flows
- Contributed to **liquidity architecture** (GLV/GM pools), share accounting, and real-yield distribution mechanics
- Designed/implemented an off-chain **Keeper**: monitors on-chain orders/events, validates prices, executes with fault-tolerance

### Magic Eden — Smart Contract Engineer
- Designed/implemented **Solana NFT AMM**: bid/ask/dual-sided pools, curve-based pricing, royalty compatibility in batch scenarios
- Built **NFT lottery / mystery box** protocol with commit–reveal style flow and full on-chain state machine (draw/fulfill/refund)
- Developed **Sui NFT launchpad**: template-based minting, soft/hard caps, presale/refund mechanics using Move resources
- Built **Solana/Sui indexing pipelines**: validator/plugin ingestion, Redis/Kafka distribution, Postgres persistence, analytics layer

### NTT Data — Senior Blockchain Engineer (Hyperledger Fabric)
- Implemented trade-document workflows as on-chain assets/state machines (permissioning, auditability, enterprise integrations)
- Designed channel-based data sharing models (private/shared/observer) for compliance-grade access control

### LBank — Senior Backend Engineer (Web3)
- Built Web3 service modules: encrypted key storage, address management, multi-chain routing, tx build/sign/broadcast
- Implemented DEX aggregation flows and CEX-side funds/ledger services with stable high-concurrency processing

---

## Tech stack
- **Languages**: Rust, Go, TypeScript/Node.js, Python, Java, Solidity, Move  
- **Chains**: Solana, Ethereum/EVM, Sui, Hyperledger Fabric  
- **Infra/Data**: Kafka, Redis, PostgreSQL, MongoDB, Databricks, AWS, Docker, Kubernetes  
- **Architecture**: microservices, event-driven systems, trading infrastructure, indexing/analytics pipelines  

---

## Open-source / repos worth checking
A few public repos related to my interests (strategies, bots, infra, protocol experiments):
- `aave-v3-liquidation-bot` — liquidation monitoring/execution tooling
- `pendle-arbitrage-system` — strategy research & implementation scaffolding
- `curve-stablecoin-strategies` — curve/Stablecoin strategy exploration
- `gmx-strategy` — strategy framework & experiments

(If you're hiring or collaborating, I can share more context privately where appropriate.)

---

## Research interests
- Consensus & core flow studies: PoW/PoS/PoH, Solana Tower BFT, Sui Narwhal/Bullshark, Polkadot/Cardano designs
- L2/Rollup transaction lifecycle and customization points (OP Stack / Polygon ecosystem)
- DeFi protocol flow mapping for integration/strategy development (DEX, lending, liquidation interfaces)

---

## Contact
- Email: **thomas_sue_wu@hotmail.com**
- Telegram: **@thomasquant**
- GitHub: https://github.com/thomasxiaodongwu

---

_If you’re working on DeFi perps, execution/keepers, Solana infra, NFT liquidity, or indexing pipelines — happy to chat._
