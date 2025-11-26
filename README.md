# ⚡ Phoenix Signal Viewer

> Real-time Rust + Solana project analyzing **order-book activity** on the [Phoenix DEX](https://phoenix.trade).  
> The goal: extract meaningful trading signals directly from on-chain data — measuring liquidity, bid/ask imbalance, and price flow in real time.

---

### 🧠 What This Is

A learning and research project exploring **Rust async programming** and **Solana’s market microstructure**.  
Starting simple, then gradually evolving:

| Version | Milestone |
|----------|------------|
| **v0.1** | Connect to Phoenix RPC + print top 5 bids/asks |
| **v0.2** | Calculate bid/ask imbalance ratio |
| **v0.3** | Display metrics in real-time (CLI dashboard) |
| **v0.4** | Stream data via WebSocket (live feed) |
| **v0.5** | Export to CSV for ML backtesting |

---

### 🧰 Stack

![Rust](https://img.shields.io/badge/Rust-000000?logo=rust&logoColor=white)
![Solana](https://img.shields.io/badge/Solana-9945FF?logo=solana&logoColor=white)
![Phoenix](https://img.shields.io/badge/Phoenix-0D1117?logo=solana&logoColor=white)
![Tokio](https://img.shields.io/badge/Tokio-333333?logo=rust&logoColor=white)

---

### ⚙️ Getting Started

```bash
# Clone and build
git clone https://github.com/glt-builds/phoenix_signal_viewer.git
cd phoenix_signal_viewer
cargo run
