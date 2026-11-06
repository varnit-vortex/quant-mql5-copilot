# VortexQuant: Institutional SMC & MQL5 Algorithmic Terminal

[![Live Demo](https://img.shields.io/badge/Live_Demo-GitHub_Pages-cyan?style=for-the-badge&logo=github)](https://varnit-vortex.github.io/quant-mql5-copilot/)
[![Upwork Profile](https://img.shields.io/badge/Upwork-Verified_AI_Engineer-14a800?style=for-the-badge&logo=upwork)](https://www.upwork.com/freelancers/~01a695e72a7445ecf2)
[![IIT Roorkee](https://img.shields.io/badge/Certified-iHUB_DivyaSampark_IIT_Roorkee-orange?style=for-the-badge)](https://www.upwork.com/freelancers/~01a695e72a7445ecf2)

> **VortexQuant** is an institutional-grade Smart Money Concepts (SMC) & MQL5 Expert Advisor (EA) Terminal. Engineered with real-time Forex Factory economic news shield, live breaking market wire feeds, institutional liquidity sweep detection, dynamic risk guardrails, and compilable MetaTrader 5 `.mq5` code synthesis.

---

## 🚀 Live Terminal Interface
Experience the live algorithmic terminal:
🔗 **[https://varnit-vortex.github.io/quant-mql5-copilot/](https://varnit-vortex.github.io/quant-mql5-copilot/)**

---

## 🏛️ System Architecture

```mermaid
flowchart TD
    A[SMC Trader Intent\n'ICT FVG + Liquidity Sweep'] --> B[VortexQuant Prompt Engine]
    B --> C{Confluence & News Radar}
    C -->|Forex Factory Red News| D[Auto-Halt EA Buffer\nPause 30m Before/After]
    C -->|Clear Market Condition| E[Risk & Lot Sizing Guard\nMax 1.5% Risk / Trade]
    E --> F[Dynamic Lot Calculator\nEquity * Risk% / SL Points * PointVal]
    F --> G[Production MQL5 Synthesis\nTrade.mqh + OnInit + OnTick + TrailingStop]
    G --> H[MetaEditor 5 Compilation]
    G --> I[FastAPI MT5 Bridge Service]
    I --> J[MetaTrader 5 VPS Execution]
```

---

## ✨ Core Highlights

### 1. Smart Money Concepts (SMC) & MQL5 Synthesis
- Translates advanced institutional logic (Asian session liquidity sweeps, Fair Value Gaps [FVG], Break of Structure [BOS], Order Blocks) into production MetaTrader 5 code.
- Uses `iTime()` bar-close confirmation to completely eliminate tick repainting.
- Dynamic lot sizing protects against margin blowouts.

### 2. Live Forex Factory Radar & Breaking Market Wire
- Dual-mode institutional news radar:
  - **Forex Factory Calendar**: Real-time high-impact 🔴 red folder event tracking (CPI, FOMC, NFP, ECB) with automated EA news shields.
  - **Live Breaking News Wire**: Real-time financial headlines (Reuters, Bloomberg) with automated sentiment impacts.

### 3. Complete TradingView-Grade Charting
- Real-time tick simulator with interactive crosshair inspection.
- Y-axis price scale with animated live price badge and dotted execution line.
- Timezone switcher: **EST (New York)**, **UTC (London)**, and **IST (Local India)**.

---

## 👨‍💻 Developer Profile

**Varnit Bhardwaj**  
*Agentic Systems & Quantitative Algorithmic Developer*  
- **Certification**: Certified in Agentic Systems and Design by **iHUB DivyaSampark, IIT Roorkee** & Masai School (9.4/10 Evaluation Score, 100% Attendance).
- **Core Skills**: Python, LangGraph, MetaTrader 5 (MQL5), Smart Money Concepts (SMC), FastAPI, RAG, Financial Time-Series.
- **Upwork Profile**: [Varnit B. on Upwork](https://www.upwork.com/freelancers/~01a695e72a7445ecf2)
