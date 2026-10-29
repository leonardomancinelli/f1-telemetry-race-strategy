# F1 Telemetry & Race Strategy Analytics 🏎️📊

📌 **Project Status:** *Active Development (Core Data Pipeline & Visualizations Release: November 2026)*

## 📖 Overview
This repository contains a specialized Python analytics suite designed to extract, process, and analyze official Formula 1 live timing and telemetry datasets. The goal of the project is to convert raw sensor data into actionable insights for race strategy evaluation and driver performance optimization.

## 🎯 Key Analytical Features
- **Driver Telemetry Overlay:** Comparative traces for speed, throttle application, braking points, and gear selection using `FastF1`.
- **Race Strategy & Tire Degradation:** Modeling stint consistency, lap-time deltas, and degradation curves across different tire compounds.
- **Track Evolution & Session Management:** Analyzing session variables and sector-by-sector performance deltas during Qualifying and Race sessions.

## 🛠️ Tech Stack & Tools
- **Language:** Python 3.x
- **Libraries:** `FastF1`, `Pandas`, `Matplotlib`, `NumPy`
- **Data Source:** Official Formula 1 Live Timing API via `FastF1`

## 📁 Repository Structure
```text
├── telemetry_scripts/    # Python scripts for data extraction & plotting
├── output_charts/         # Generated telemetry overlays and degradation plots
└── README.md              # Project documentation
---
*Developed by **Leonardo Mancinelli** — B.Sc. Mechanical Engineering Student at University of Perugia (UniPG)*
