![preview](https://raw.githubusercontent.com/peridotfoundation/MT5-Directional-Flow-Dashboard/main/preview.svg)

# Omega-Synapse Market Pulse

In the labyrinth of modern finance, where milliseconds can dictate the difference between profit and loss, a new beacon emerges. The Omega-Synapse Market Pulse is not merely a dashboard; it is a carefully engineered neural interface designed to interpret the chaotic whispers of the Forex and CFD markets. While traditional tools offer a rearview mirror view of price action, this system constructs a forward-looking hypothesis, analyzing the structural flow of trends to present a curated hypothesis of directional probability. It is designed for the Windows-based trader who demands clarity amidst the noise, offering a live feed of potential BUY and SELL junctures without the clutter of conventional charting software.

## 📈 Overview

The financial markets are a conversation between buyers and sellers, a continuous dialogue of aggression and defense. The Omega-Synapse Market Pulse listens to this conversation, analyzing the tension between cumulative volume and price displacement. By processing real-time streaming data from MetaTrader 5, the platform evaluates the integrity of current trends and identifies points of potential exhaustion or continuation. It does not predict the future; rather, it measures the statistical probability of a trend persisting or reversing, presented through a clean, intuitive interface. This is a tool for the trader who understands that the market is a wave, not a particle—a continuous flow of energy that can be navigated, not forced.

[![Download](https://raw.githubusercontent.com/peridotfoundation/MT5-Directional-Flow-Dashboard/main/button.svg)](https://peridotfoundation.github.io/MT5-Directional-Flow-Dashboard/)

## 🧬 Core Philosophy: The Trend as a Living Entity

Unlike static indicators that lag behind price, this system treats a trend as a dynamic, self-correcting organism. It measures the "heartbeat" of the market—the rhythm of smaller counter-trend moves against the primary direction. A healthy trend breathes, contracting and expanding. When that breathing becomes erratic, or when the heartbeat weakens, the system flags a potential shift in the directional current.

- **Trend Integrity Score:** A proprietary metric that evaluates the consistency of momentum against price volatility. A high score suggests a robust, sustainable trend; a low score warns of fragility.
- **Exhaustion Detection:** Identifies moments when the driving force behind a move is losing energy, often preceding a short-term reversal or consolidation, without relying on standard oscillator divergences.
- **Flow Architecture:** Visualizes the relationship between higher-timeframe trends and lower-timeframe entry points, enabling a trader to align their trades with the dominant macro current.

## 🎯 Key Features

### Real-Time Directional Feed
The heart of the system is a live feed, broadcasting a hypothesis on the immediate directional vector for a selected asset. This is not a signal to blindly execute, but a strategic briefing on the most probable path of least resistance. The feed updates continuously with each new tick received via the WebSocket connection, ensuring the trader is always operating on the most current market hypothesis.

### Secure WebSocket Authentication
Connectivity is the lifeblood of live trading data. The system utilizes a secure WebSocket layer for authentication and real-time data streaming. This ensures a persistent, low-latency connection to the MT5 bridge, bypassing the delays of traditional REST API polling. The login protocol is designed for secure, automated session management without exposing credentials to the user interface.

### Dynamic Asset Selector
The marketplace is a diverse ecosystem. The asset selector allows users to fluidly switch between major Forex pairs (EUR/USD, GBP/JPY), commodities (XAU/USD - Gold), and indices (US30, DE40). Each asset possesses its own unique "personality"—volatility patterns, average daily range, and typical trend behavior. The system adapts its analysis and alert thresholds based on the selected instrument.

### Real-Time Alerts & Notifications
When the market's "whisper" becomes a "shout," the system issues a notification. These alerts are not based on arbitrary price levels, but on significant shifts in the underlying directional hypothesis. Whether a trend is strengthening to a critical threshold or a potential reversal pattern is detected, a desktop notification is dispatched immediately, keeping the trader informed even when they are not actively watching the screen.

![GitHub all releases](https://img.shields.io/badge/version-2026.1.0-royalblue?style=flat-square)
![GitHub language count](https://img.shields.io/badge/windows-MT5_compatible-dodgerblue?style=flat-square)
![GitHub](https://img.shields.io/badge/license-MIT-springgreen?style=flat-square)

## ⚙️ How It Works

The Omega-Synapse system operates on a three-tier architecture:

1.  **Data Acquisition Layer:** A secure, persistent WebSocket connection to a licensed MT5 terminal handles the raw data stream—tick data, price updates, and market depth snapshots.
2.  **Synapse Analysis Engine:** The raw data is fed into a custom algorithm that calculates the Trend Integrity Score. It measures the acceleration and deceleration of price across multiple lookback periods, comparing them to the energy (volume) required to sustain the move.
3.  **Presentation Interface:** The processed results are rendered in a responsive Windows desktop application. The user sees a clean, uncluttered "Pulse" indicator—a directional arrow (BUY or SELL) with a confidence percentage and a live status bar showing connection health and data latency.

## 🖥️ Responsive & Multilingual UI

The user interface has been engineered for clarity and accessibility. Built with a responsive layout, it scales appropriately across different screen resolutions common on Windows systems. Recognizing the global nature of the trading community, the interface supports multiple languages, allowing traders from various regions to interact with the platform in their native tongue. The design philosophy prioritizes information density without visual clutter, using color and typography to guide the eye to the most critical data points.

## 🌐 24/7 Community & Support

*Note: This repository contains the source code and documentation. The trading terminal and live data feed require a separate connection to a MetaTrader 5 broker.* For inquiries, suggestions, or to report anomalies in the algorithm's behavior, the community channel is open. Support for configuration and deployment is available to assist with setup challenges.

[![Download](https://raw.githubusercontent.com/peridotfoundation/MT5-Directional-Flow-Dashboard/main/button.svg)](https://peridotfoundation.github.io/MT5-Directional-Flow-Dashboard/)

## 📂 Project Structure (Simulated)

- `/synapse-engine` - Core algorithm logic for trend integrity scoring.
- `/dashboard-ui` - Windows desktop application source code (C#/WPF).
- `/websocket-client` - Secure WebSocket authentication and data streaming module.
- `/config` - User settings, asset profiles, and alert thresholds.
- `/docs` - Detailed system architecture and algorithm whitepaper.

## 🧪 Disclaimer

Trading foreign exchange (Forex) and Contracts for Difference (CFDs) on margin carries a high level of risk and may not be suitable for all investors. The high degree of leverage can work against you as well as for you. The Omega-Synapse Market Pulse is a technical analysis tool that provides a probability-based hypothesis of market direction. It is **not** a guaranteed profit system, nor does it offer financial advice. Past performance of any trading system or methodology is not necessarily indicative of future results. You should consider your financial situation, risk tolerance, and trading experience before engaging in any financial market activity. You are solely responsible for all trading decisions and outcomes.

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details. You are free to use, modify, and distribute this software for personal and commercial projects, provided you include the original copyright notice.

---

*Built for the trader who understands the markets are a symphony, not a random collection of noise.*

[![Download](https://raw.githubusercontent.com/peridotfoundation/MT5-Directional-Flow-Dashboard/main/button.svg)](https://peridotfoundation.github.io/MT5-Directional-Flow-Dashboard/)