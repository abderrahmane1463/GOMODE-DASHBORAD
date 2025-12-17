# GOMODE-DASHBORAD
# GoMode COD Analytics Dashboard

## Internship Project

This repository contains an **end-to-end data analytics dashboard** developed as part of an **internship project**. The goal of the project is to analyze **Cash on Delivery (COD) logistics operations** and provide actionable insights to improve delivery performance, reduce returns, and optimize revenue collection.

The application is built using **Python** and **Streamlit**, and it consumes real-time data from a logistics API.

---

## Project Objectives

* Monitor COD logistics performance in real time
* Analyze delivery delays and operational bottlenecks
* Measure success rate, return rate, and revenue impact
* Identify high-risk areas (wilayas, hubs, customers)
* Support decision-making with clear KPIs and visualizations

---

## Features

* 🔄 **Live API Integration** with pagination, rate limiting, and caching
* 📊 **Interactive Dashboard** built with Streamlit
* 📈 **Key Performance Indicators (KPIs)**

  * Total orders
  * Success rate
  * Return rate
  * Average processing and delivery time
* ⏱️ **Time Analysis**

  * Processing time (creation → expedition)
  * Shipping time (expedition → last status)
* 📍 **Geographical Analysis**

  * Orders and revenue by wilaya
  * Cash collection rate by wilaya
* 🚦 **Bottleneck Detection**

  * Slowest deliveries
  * Hubs with high delays
* 💰 **Revenue Analysis**

  * Successful COD revenue
  * Lost revenue due to returns
* 🚨 **Risk Analysis**

  * High-return areas
  * Blacklist of customers with frequent returns
* 📦 **Product Analysis**

  * Most returned products
  * Price vs declared value comparison

---

## Technologies Used

* **Python 3**
* **Streamlit** – dashboard and UI
* **Pandas** – data manipulation
* **Plotly** – interactive visualizations
* **Requests** – API communication

---

## Data Source

* Data is retrieved from a **private logistics API** (COD parcel data).
* The dashboard includes:

  * Secure API authentication
  * Exponential backoff & retry logic
  * Caching to reduce API load


## Key Insights Provided

* Identification of delays between order creation and expedition
* Detection of inefficient delivery routes or hubs
* Measurement of revenue losses caused by returned orders
* Recognition of high-risk customers and regions
* Support for operational and strategic decisions

---

## Internship Context

This project was developed as part of an **internship in data analysis / logistics analytics**. It demonstrates:

* Practical use of Python for real-world data
* API data handling and robustness
* Data cleaning and feature engineering
* KPI design and business-oriented analytics
* Dashboard development and data storytelling

---

## Author

**Houssam Cherfaoui**
Statistics & Data Science Student

---

## Disclaimer

This project is for **educational and analytical purposes only**. All sensitive or private information should be anonymized before public deployment.

---

⭐ If you find this project interesting, feel free to star the repository!
