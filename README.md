# Fuel Cell Durability Estimator (v1.0-MVP)

An engineering workbench designed to accelerate fuel cell stack health diagnostics. This tool allows validation and calibration engineers to transform raw vehicle CAN bus telemetry logs into immediate, actionable health indicators—specifically **State of Health (SOH%)** and **Remaining Useful Life (RUL)** hours—drastically reducing data processing loops from days to under 120 seconds.

![Dashboard Preview](image_347866.png)

## 🚀 Core Features (Wave 1 MVP)

* **Multi-Format Log Ingestion:** High-capacity manual file upload area designed for automotive data scales (up to 500 MB).
* **Automotive File Support:** Native ingestion handling for standard engineering log formats: `.mf4`, `.mdf`, `.blf`, `.csv`, and `.parquet`.
* **Durability Calculation Engine:** Backend execution pipeline that maps raw CAN bus signals (current, voltage, temperature) to evaluate electrochemical degradation.
* **SOH & RUL Dashboard View:** Clean, scannable UI layout prioritizing the two core health metrics with clear baseline tracking.

---

## 🛠️ Tech Stack

* **Frontend/Dashboard:** Python (Streamlit framework for high-performance engineering UI rendering)
* **Data Processing Engine:** DuckDB / Pandas (optimized for handling large-scale tabular time-series telemetry datasets)
* **Core Model Execution:** Python-packaged analytical calculation scripts

---

## 🏁 Getting Started

### Prerequisites
Ensure you have Python 3.10+ installed locally.

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/Guiga1993/MVP_Canvas.git
   cd MVP_Canvas
   ```
