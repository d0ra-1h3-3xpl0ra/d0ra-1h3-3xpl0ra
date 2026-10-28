### What I work on

- **Trading systems** — market data, execution and risk
- **Arbitrage and MEV** — on-chain strategies across DEXs and CEXs
- **DeFi** — protocols and vault strategies
- **Data platforms** — crypto risk ratings at scale
- **Due diligence** — technical and code review of early-stage startups

### Open source

Fixing correctness and performance bugs in trading, data and networking infrastructure.

| Project | Work | Status |
|---|---|---|
| [tokio](https://github.com/tokio-rs/tokio) | Release the I/O driver's fds when a runtime shuts down | [#8703](https://github.com/tokio-rs/tokio/issues/8703) · proposed |
| [simd-json](https://github.com/simd-lite/simd-json) | Propose the fix for O(n²) parsing on repeated keys | [#491](https://github.com/simd-lite/simd-json/issues/491) · fixed upstream by maintainer |
| [smoltcp](https://github.com/smoltcp-rs/smoltcp) | Fix TCP stall after simultaneous ACK loss | [#1221](https://github.com/smoltcp-rs/smoltcp/issues/1221) · proposed |
| [nautilus_trader](https://github.com/nautechsystems/nautilus_trader) | Periodic instrument refresh for Deribit | [#5465](https://github.com/nautechsystems/nautilus_trader/pull/5465) · approved |
| [datafusion](https://github.com/apache/datafusion) | Fix sort-merge semi/anti joins on timezone-aware timestamp and other key types | [#26830](https://github.com/apache/datafusion/pull/26830) · merged |
| [datafusion](https://github.com/apache/datafusion) | Stop window top-N queries pinning whole string buffers (463 MB → 3 MB) | [#26857](https://github.com/apache/datafusion/pull/26857) · in review |
| [mio](https://github.com/tokio-rs/mio) | Fix lost Waker wake-ups in the poll(2) selector | [#2032](https://github.com/tokio-rs/mio/pull/2032) · in review |
| [quanta](https://github.com/metrics-rs/quanta) | Fall back to the OS clock when Linux reports the TSC as unstable | [#123](https://github.com/metrics-rs/quanta/pull/123) · in review |
| [reth](https://github.com/paradigmxyz/reth) | Fix `eth_capabilities` reporting archive receipts as pruned | [#28178](https://github.com/paradigmxyz/reth/pull/28178) · in review |
| [simple-binary-encoding](https://github.com/aeron-io/simple-binary-encoding) | Set presence on optional enum encodings in the IR (CME iLink schemas) | [#1146](https://github.com/aeron-io/simple-binary-encoding/pull/1146) · in review |

### Stack

| Area | Tools |
|---|---|
| Languages | `Rust` `Python` `Solidity` `Huff` `Assembly` `TypeScript` `Go` `Vyper` `SQL` `Java` |
| Rust | `Tokio` `async/await` `tokio-tungstenite` `axum` `hyper` `reqwest` `sqlx` `serde` `Arrow/Parquet` `tracing` `Cargo workspaces` `cargo-deny` |
| Java | `Java 26` `Spring Boot 4` `Spring Modulith` `Spring Security / OAuth2` `JPA` `Flyway` `Maven` `OpenTelemetry` `SBE` |
| Python | `Polars` `pandas` `NumPy` `DuckDB` `PyArrow` `Pydantic` `NautilusTrader` `marimo` `Jupyter` |
| Research | `market microstructure` `order books` `adverse selection` `maker/taker economics` `time-series` `backtesting` `bootstrap CIs` `pre-registered tests` |
| Trading & execution | `MEV` `Flashbots` `arbitrage` `CEX/DEX connectivity` `WebSocket` `REST` `JSON-RPC` `risk controls` `reconciliation` |
| Systems | `async runtimes` `epoll/kqueue` `TCP` `WebSocket feeds` `Linux` |
| Testing & correctness | `TDD` `integration & regression tests` `Foundry fuzz & invariant tests` `mutation testing (PIT)` `JUnit 5` `Testcontainers` `WireMock` `ArchUnit` `Checkstyle` `SpotBugs` `PMD` `JaCoCo` `CI quality gates` |
| Observability | `tracing` `structlog` `Grafana` `alerting` `Langfuse` `latency measurement (p50)` `ledger reconciliation checks` |
| Smart contracts | `Foundry` `Hardhat` `OpenZeppelin` `Tenderly` `Safe` `ERC-4626` `ERC-4337` |
| Ethereum clients & libraries | `Geth` `Nethermind` `Reth` `ethers.js` `web3.py` `ethers-rs` `alloy` `Dune` `The Graph` `Nansen` |
| Databases | `PostgreSQL` `ClickHouse` `DuckDB` `Parquet` |
| Data engineering | `Spark` `Airflow` `Kafka` `Redpanda` `batch & streaming pipelines` |
| AI engineering | `LLM harnesses` `RAG` `LangChain` `Langfuse` `MCP` `Claude Code` |
| Infrastructure | `Kubernetes` `Helm` `Docker` `Terraform` `GCP (Cloud Build, Pub/Sub, KMS, Secret Manager)` `AWS (Nitro Enclaves, IAM, S3, Cognito, KMS)` `GitHub Actions` `osv-scanner` `Proxmox` `systemd` |
