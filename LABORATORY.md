# Bitcoin Energy Observatory (BEO): Laboratory-Scale Research Project Proposal

---

## 1. Executive Summary

This proposal seeks funding for **Project A: the BEO Laboratory-Scale Research Project**, which establishes the Bitcoin Energy Observatory as a **scientific monitoring instrument**, analogous to a weather station, for measuring the physical relationship between energy input and Bitcoin output.

The project consists of a **single, off-grid research installation** combining renewable energy generation and ASIC Bitcoin mining, fully instrumented and continuously monitored. Its purpose is not commercial mining, but **high-resolution data collection**, producing an empirical baseline for understanding Bitcoin mining as an energy-mediated physical process.

This laboratory-scale project forms the **foundational measurement layer** for all subsequent BEO deployments, including real-world agricultural and land-use studies. It defines the hardware, data standards, and analytical methods that allow Bitcoin-energy research to move from inference to direct observation.

---

## 2. Background and Motivation

Bitcoin mining is often discussed in aggregate terms—global energy consumption, average electricity prices, or modeled miner behavior. These approaches rely heavily on assumptions and indirect inference, resulting in wide uncertainty and limited falsifiability.

Earlier discussions motivating the BEO concept proposed treating Bitcoin mining like a **meteorological phenomenon**: instead of estimating global behavior, deploy many small, standardized instruments—"Bitcoin weather stations"—that directly observe local conditions and report consistent measurements over time.

The BEO Laboratory-Scale Project operationalizes this idea by creating the first such station: a controlled, off-grid installation that continuously measures energy generation, energy consumption, and Bitcoin output, synchronized with Bitcoin network and market data.

---

## 3. Research Aims

### Primary Aim

To establish and validate a **repeatable, off-grid measurement system** that empirically quantifies the relationship between:

* Energy input (kWh)
* Bitcoin output (BTC)
* Bitcoin network conditions
* Bitcoin market price

### Secondary Aims

1. Develop a standardized "Bitcoin energy weather station" architecture.
2. Produce a high-quality, open dataset linking physical energy flows to Bitcoin outputs.
3. Measure the variability of BTC/kWh under fixed physical conditions.
4. Observe protocol-driven effects such as difficulty adjustment and halving events.
5. Provide a baseline against which field deployments can be compared.

---

## 4. Core Research Questions

1. What is the empirically observed conversion rate between energy (kWh) and Bitcoin (BTC) under controlled, off-grid conditions?
2. How does this conversion rate vary over time, independent of local energy price signals?
3. Do changes in Bitcoin’s market price lead or lag changes in locally observed BTC/kWh?
4. How do Bitcoin protocol events manifest in direct physical measurements?

---

## 5. System Overview (Laboratory Installation)

### 5.1 Physical Configuration

The laboratory-scale BEO station defines a clear **control volume**:

* Renewable energy generation (solar PV)
* Optional energy storage (battery)
* Power conditioning (MPPT, inverter)
* ASIC Bitcoin mining hardware
* Revenue-grade energy metering

Operating off-grid eliminates ambiguity around electricity pricing and ensures that all measured energy inputs are locally generated and directly accounted for.

### 5.2 Why Off-Grid

Off-grid operation:

* Removes dependence on market electricity prices
* Avoids grid arbitrage or regulatory artifacts
* Ensures energy input is a measurable physical quantity
* Introduces natural variability (weather) independent of Bitcoin markets

---

## 6. Data Collection and Monitoring

### 6.1 Local Physical Measurements

Collected continuously:

* Energy generated (kWh)
* Energy consumed by miners (kWh)
* ASIC hashrate and uptime
* BTC earned (subsidy + fees)
* Environmental variables (temperature, irradiance)

### 6.2 Network and Market Data

Time-aligned external data:

* Bitcoin network hashrate
* Network difficulty
* Block subsidy and fees
* BTC/USD price

### 6.3 Time Resolution

All variables recorded in consistent time bins (hourly and daily), enabling direct comparison without interpolation artifacts.

---

## 7. Hypotheses

### H1: Physical Stability Hypothesis

> Under fixed hardware and energy conditions, BTC/kWh remains statistically bounded despite market volatility.

### H2: Market Signal Hypothesis

> Changes in Bitcoin market price lead changes in BTC/kWh through miner competition and difficulty adjustment.

### H3: Protocol Visibility Hypothesis

> Bitcoin protocol events (e.g., halving) produce discrete, observable signatures in local energy-to-BTC measurements.

---

## 8. Expected Outcomes

* A validated Bitcoin energy monitoring instrument
* Empirical BTC/kWh time series data
* Evidence-based insights into Bitcoin’s energy conversion behavior
* A reproducible experimental protocol
* Open datasets suitable for academic and policy research

---

## 9. Role Within the BEO Programme

This laboratory-scale project serves as **Project A** within the broader BEO research programme:

* It defines instrumentation standards and data schemas
* It provides baseline measurements
* It de-risks subsequent deployments

All future BEO installations—including agricultural and land-use studies—will use this project as their reference framework.

---

## 10. Equipment Annex (Laboratory Installation)

### Energy Generation

* Solar PV panels (1–5 kW)
* Mounting hardware

### Energy Storage & Power Electronics

* LiFePO₄ battery bank
* MPPT charge controller
* Pure sine wave inverter

### Mining Hardware

* ASIC miner(s) (e.g., Antminer S19 class)
* Power tuning firmware

### Instrumentation & Monitoring

* Revenue-grade energy meters (AC & DC)
* Environmental sensors
* Hashrate and uptime monitoring
* Time-synchronized data logger

### Data & Connectivity

* Local data storage
* Secure remote access
* Open-source data pipeline

---

## 11. Conclusion

The BEO Laboratory-Scale Research Project establishes Bitcoin mining as a **measurable physical process** through direct observation rather than inference. By creating a Bitcoin equivalent of a weather station, it lays the empirical foundation necessary for rigorous scientific study and informed policy discussion.


