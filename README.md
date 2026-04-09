<div align="center">

```
██████╗ ██╗  ██╗ ██████╗ ████████╗
██╔══██╗██║  ██║██╔═══██╗╚══██╔══╝
██║  ██║███████║██║   ██║   ██║   
██║  ██║██╔══██║██║   ██║   ██║   
██████╔╝██║  ██║╚██████╔╝   ██║   
╚═════╝ ╚═╝  ╚═╝ ╚═════╝    ╚═╝  
        N E T W O R K S
```

### Building the tools the market doesn't have — yet.

[![Zig](https://img.shields.io/badge/Zig-0.15.2-F7A41D?style=flat-square&logo=zig&logoColor=white)](https://ziglang.org/)
[![Go](https://img.shields.io/badge/Go-1.22+-00ADD8?style=flat-square&logo=go&logoColor=white)](https://golang.org/)
[![Blockchain](https://img.shields.io/badge/Blockchain-EVM%20%7C%20RISC--V%20%7C%20PolkaVM-6C47FF?style=flat-square)](#)
[![GUI](https://img.shields.io/badge/GUI-zgui%20%2B%20implot-00C896?style=flat-square)](#)
[![Open Source](https://img.shields.io/badge/Open%20Source-Yes-brightgreen?style=flat-square)](#)

</div>

---

## ⚡ What I Build

I work at the **intersection of systems programming and financial technology** — low-level, high-performance, zero-dependency tools that run everywhere and depend on nothing.

No Electron. No Python runtimes. No cloud lock-in. Just compiled binaries that work.

---

## 🚀 Featured Projects

<br>

### 🔗 Zephyria — A New Blockchain Runtime

> *A production-grade blockchain VM and smart contract compiler, written from scratch in Zig.*

```
Forge Language (.foz) → forgec Compiler → ZephBin Binary → ZephyriaVM Execution
                              ↓
              RISC-V RV64IM / EVM / PolkaVM Backends
```

**What makes it different:**

| Feature | Description |
|--------|-------------|
| 🦺 **Forge Language** | A new smart contract language with first-class authority guards, linear capability types, and conservation proofs |
| 🧠 **ZephyriaVM** | A custom RISC-V RV64IM interpreter with a sandboxed execution model and per-opcode gas metering |
| ⚙️ **Multi-Backend Codegen** | Compiles to RISC-V, EVM bytecode, and PolkaVM WASM from a single frontend |
| 🔒 **Adversary Blocks** | Built-in adversary simulation at the language level — think fuzzing, but in your contract spec |
| 📐 **Conservation Proofs** | Formal conservation expressions (`conserves`) enforced at compile time, not runtime |
| 📦 **ZephBin v1** | Custom binary format with BLAKE3 checksums, ABI JSON, and signed access-list descriptors |

**Stack:** `Zig 0.15.2` · `~18,500+ LOC` · `13 compiler passes` · `3 codegen backends`

<br>

---

### 📈 Stock Jedi — Bloomberg in Your Terminal

> *A free, open-source, professional NSE trading terminal. No subscription. No browser. No bloat.*

```
┌─────────────────────────────────────────────────────────────┐
│  WATCHLIST  │         CANDLESTICK CHART (Unicode)           │
│─────────────│──────────────────────────────────────────────│
│  RELIANCE   │   ▄█▀█▄  ▀█  █▄▀█  ▄▄  Real-time OHLCV      │
│  TCS        │  ▀   ▀█▄ █▄▀  ▄█▀  ██  Yahoo Finance v8      │
│  NIFTY50    │                         No auth required      │
│─────────────│──────────────────────────────────────────────│
│  F&O CHAIN  │   CE OI │ Strike │ PE OI │ IV │ Greeks       │
└─────────────────────────────────────────────────────────────┘
```

**Why it exists:** Bloomberg Terminal costs $24,000/year. Zerodha/Kite is browser-only. Nothing gives you a fast, keyboard-driven, offline-capable NSE terminal — until now.

| Feature | Detail |
|---------|--------|
| 📡 **Live Quotes** | Real-time NSE data via Yahoo Finance free API (`SYMBOL.NS`) |
| 🕯️ **Candlestick Charts** | Full Unicode block-character OHLCV charts with ANSI colors, in-terminal |
| 📊 **F&O Options Chain** | Live options chain with OI, IV, and Greeks |
| ⚡ **Single Binary** | Cross-platform. macOS, Windows, Linux. Zero install. |
| 🔄 **Background Refresh** | Goroutine-based thread-safe cache with configurable refresh intervals |
| 🎯 **Keyboard-Driven** | Full Bloomberg-style hotkey navigation |

**Stack:** `Zig 0.15.2` · `Dear ImGui` · `SDL2` · `Yahoo Finance v8 API` · `JSON config persistence`

---

## 🛠️ Tech Stack

```
Languages       │  Zig 0.15.2 · (expanding)
Compilers/VMs   │  Custom Zephyria RISC-V interpreter · EVM emitter · PolkaVM codegen
GUI             │  Dear ImGui · SDL2 · Unicode rendering
Data            │  Yahoo Finance v8 · NSE market data · REST/JSON
Storage         │  ZephBin v1 (custom) · JSON config · Thread-safe in-memory cache
Tooling         │  Single-binary distribution · No external runtimes · Cross-platform
```

---

## 🧭 Roadmap

**Stock Jedi**
- [ ] Technical indicators (RSI, MACD, Bollinger Bands)
- [ ] News RSS feed panel
- [ ] Global markets & forex panel
- [ ] Paper trading simulator

**Zephyria**
- [ ] ZK proof integration flag (`0x04` in ZephBin header)
- [ ] Parallel execution model (`#[parallel]` actions)
- [ ] Full test suite with adversary simulation harness
- [ ] Forge language spec documentation

---

## 💬 Philosophy

> *"The best tool is the one that disappears. You shouldn't notice it — you should only notice the work."*

I build for developers and traders who are tired of:
- Paying for things that should be free
- Running Electron apps for 2MB of functionality  
- Waiting on cloud APIs for data they can fetch themselves

Everything here is **free, open-source, and compiled to a single binary**.

---

## 📫 Connect

<div align="center">

[![GitHub](https://img.shields.io/badge/GitHub-DHOTNetworks-181717?style=for-the-badge&logo=github)](https://github.com/DHOTNetworks)

*If any of this resonates — star a repo, open an issue, or just say hi.*

</div>

---

<div align="center">
<sub>Built with Zig · Go · and an unhealthy obsession with compile-time correctness</sub>
</div>
