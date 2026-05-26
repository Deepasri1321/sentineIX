# SentinelX - AI Market Surveillance Platform

SentinelX is a real-time market surveillance platform designed to detect potential insider trading, pump-and-dump schemes, and anomalous market manipulation. By leveraging AI-driven analytics, the platform processes stock data, news sentiment, and social media trends to provide a comprehensive risk assessment for investors and compliance teams.

## 🚀 Features

* **Real-time Anomaly Detection:** Tracks suspicious trading volumes and price movements.
* **AI-Powered Risk Engine:** Calculates a manipulation probability score for major assets.
* **Sentiment Analysis:** Analyzes news sentiment and correlates it with market activity.
* **Social Intelligence:** Monitors social media (Twitter, Reddit, Telegram, etc.) for coordinated sentiment spikes.
* **Insider Network Analysis:** Visualizes potential links between traders and flagged market activities.
* **Interactive Dashboard:** A sleek, dark-mode UI built for high-stakes data visualization.

## 🛠 Tech Stack

* **Frontend:** HTML5, Tailwind CSS, JavaScript (ES6+).
* **Visualization:** Chart.js for real-time market and risk metrics.
* **Data Source:** [Alpha Vantage API](https://www.alphavantage.co/) for real-time financial market data.
* **Styling:** Custom CSS with Glassmorphism effects.

## 📋 Prerequisites

To run this project, you need:
1. A modern web browser.
2. An **Alpha Vantage API Key** (You can get a free one [here](https://www.alphavantage.co/support/#api-key)).

:🏗 Architectural OverviewSentinelX 

Architectural OverviewSentinelX  is engineered as a high-performance Client-Side Data Visualization Dashboard. The architecture focuses on modularity, enabling real-time financial surveillance through asynchronous data processing and reactive UI updates.System ArchitectureThe application follows a decoupled design where the Data Layer, Logic Engine, and Presentation Layer operate independently to ensure smooth interactivity.Data Pipeline & LogicIngestion Layer: Asynchronous fetch calls interface with the Alpha Vantage REST API to retrieve real-time daily time-series data.Surveillance Engine: * Heuristic Processing: The core logic performs rapid statistical analysis on price volatility and volume shifts.Risk Scoring: A proprietary algorithm calculates a "Manipulation Probability" (0–100%) by comparing current market variances against historical norms.Presentation Layer: * State Management: An event-driven showSection function handles DOM rendering, allowing for zero-latency switching between dashboard modules.Dynamic Visualization: Integration with Chart.js allows for real-time rendering of market trends, risk charts, and social sentiment radars.Component BreakdownModuleTechnologyResponsibilityUI/UXTailwind CSSResponsive, "Glassmorphic" interfaceLogic EngineVanilla JavaScript (ES6+)Statistical risk calculation & API orchestrationVisualizationChart.jsReal-time graph rendering & data mappingData LayerAlpha Vantage APIExternal source for financial time-series data
