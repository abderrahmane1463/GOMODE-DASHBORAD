<h1 align="center">GOMODE — COD Logistics Analytics Dashboard</h1>

<p align="center">
  <em>Real-time Cash on Delivery performance monitoring: delivery rates, regional bottlenecks, and revenue loss from returns</em>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.10+-3776AB?style=flat-square&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white"/>
  <img src="https://img.shields.io/badge/Plotly-3F4F75?style=flat-square&logo=plotly&logoColor=white"/>
  <img src="https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white"/>
</p>

---

## Overview

An end-to-end analytics dashboard for GOMODE's Cash on Delivery (COD) logistics operations, built during a data analytics internship. The dashboard connects to a live logistics API, processes parcel-level data, and surfaces actionable KPIs to reduce return rates, detect hub bottlenecks, and quantify revenue lost to failed deliveries.

## Features

- Live API integration with pagination, rate limiting, and exponential-backoff retry logic
- Core KPIs: total orders, success rate, return rate, average processing and delivery time
- Time analysis: processing time (creation → expedition) and shipping time (expedition → last status)
- Geographical breakdown: orders, revenue, and cash collection rate by wilaya (region)
- Hub bottleneck detection: slowest deliveries and high-delay hubs
- Revenue analysis: successful COD revenue vs. revenue lost to returns
- Risk profiling: high-return wilayas and a customer blacklist for frequent returners
- Product analysis: most returned products and declared vs. actual value comparison

## Tech Stack

| Category | Tools |
|----------|-------|
| Language | Python 3 |
| Dashboard | Streamlit |
| Visualisation | Plotly |
| Data Manipulation | pandas |
| API Communication | requests |

## Getting Started

```bash
git clone https://github.com/abderrahmane1463/GOMODE-DASHBORAD.git
cd GOMODE-DASHBORAD
pip install -r requirements.txt
streamlit run fin.py
```

> A valid GOMODE logistics API key is required. Store it as an environment variable before running.

## Results / Key Insights

- Identified significant processing time gaps between order creation and expedition, enabling targeted SLA improvements
- Revealed which wilayas concentrate the highest return rates, informing geographic risk-scoring for future orders
- Quantified revenue leakage from returned parcels, providing a clear business case for proactive customer risk management

---

<p align="center">Made by <a href="https://github.com/abderrahmane1463">Cherfaoui Houssam Abderrahmane</a></p>
