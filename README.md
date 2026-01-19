# 📈 TradingApp (C#/.NET)

A high-frequency real-time trading dashboard built with .NET and WPF. This application simulates a live market environment by processing rapid price updates and visualizing market trends through a dynamic UI.

## 🚀 Key Features

* **Real-Time Price Engine:** A dedicated service simulates live market volatility by broadcasting price update events 20 times per second (20Hz).
* **Dynamic UI Feedback:** The WPF frontend features a reactive coloring scheme to visualize price movements instantly:
* 🔵 **Blue:** Price Increase (Bullish movement)
* 🔴 **Red:** Price Decrease (Bearish movement)
* ⚪ **Light Gray:** No change


* **Event-Driven Architecture:** Demonstrates decoupling between the data simulation service and the UI layer.

## 🛠 Tech Stack

* **Language:** C#
* **Framework:** .NET / WPF (Windows Presentation Foundation)
* **Logic:** Event-based notifications and `System.Math` for randomized price generation.

## 🏁 Getting Started

### Prerequisites

* Visual Studio (2022 recommended; compatible with 2013/2015)
* .NET Desktop Development workload installed

### Installation & Run

1. **Clone the repository:**
```bash
git clone https://github.com/your-username/TradingApp.git

```


2. **Open the solution:** Launch `TradingApp.sln` in Visual Studio.
3. **Set Startup Project:** Right-click the **WPFTradeApp** project in the Solution Explorer and select **Set as Startup Project**.
4. **Execute:** Press `F5` or click **Start** to run the simulation.

> [!NOTE]
> All instrument prices are generated using a random distribution for simulation purposes and do not reflect real-market data.

---
