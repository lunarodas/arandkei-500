# Arandkei 500 Index (ARK500)

[![Index Type](https://img.shields.io/badge/Index%20Type-Equal%20Weight-blue)](#3-weighting--rebalancing)
[![Universe](https://img.shields.io/badge/Universe-US%20Non--S%26P-green)](#2-eligibility--exclusions)
[![Governance](https://img.shields.io/badge/Governance-Quarterly%20Rebalance-orange)](#3-weighting--rebalancing)

The **Arandkei 500 Index** measures the performance of 500 major operating corporations listed on U.S. stock exchanges (NYSE, NASDAQ, and NYSE American) that operate outside the official S&P index framework. 

Serving as an independent institutional benchmark, the index tracks the primary economic layer of non-indexed, non-S&P U.S. equity capital traded in U.S. Dollars (USD).

---

## 1. Key Index Highlights

* **Constituent Count:** Fixed targeted component count of **500 equities**.
* **Weighting Scheme:** **Equal-Weighted (0.20% per component at rebalance)**.
* **Coverage:** NYSE, NASDAQ, and NYSE American (AMEX).
* **Concept:** Non-S&P core equity layer ("National League" / non-indexed operating corporate space).
* **Rebalance Frequency:** Quarterly (last business day of March, June, September, and December).

---

## 2. Eligibility & Exclusions

To maintain index purity, transparency, and replicability, components must strictly pass the following criteria:

### Included
* Operating C-Corporations (Common Stock).
* Direct primary listings on **NYSE**, **NASDAQ**, or **NYSE American (AMEX)**.
* Securities traded and settled in **USD**.

### Excluded
* **Active S&P Index Constituents:** Any company currently included in the S&P 500, S&P 400, or S&P 600 indices.
* **Non-Operating & Special Structures:**
  * American Depositary Receipts (**ADRs**) and foreign cross-listings.
  * Master Limited Partnerships (**MLPs**) and Limited Partnerships (**L.Ps**).
  * Business Development Companies (**BDCs**).
  * Special Purpose Acquisition Companies (**SPACs**) and shell corporations.
  * Exchange-Traded Funds (**ETFs**), Closed-End Funds (**CEFs**), and pooled investment vehicles.

---

## 3. Weighting & Rebalancing

### Equal-Weight Structure
The Arandkei 500 operates under a strict **Equal-Weighted methodology**:
* At the close of each quarterly rebalance date, every constituent is reset to an equal weighting of **0.20% ($1/500$)**.
* Between rebalance dates, individual weights float dynamically according to daily price performance.

### Post-S&P Synchronized Schedule & Promotion Mechanics
The index functions as the natural tier directly below the S&P ecosystem:
1. **Promotion (S&P Inclusions):** Following mid-month official S&P index rebalance announcements, any Arandkei 500 constituent selected to join an S&P index is flagged for automatic removal due to promotion.
2. **Replacement Selection:** Replacement constituents are selected from the non-S&P eligible universe via the proprietary Arandkei evaluation framework.
3. **Execution Date:** All additions, deletions (promotions), and weight resets take effect at the **close of the last business day** of the rebalance month (Q1: Mar, Q2: Jun, Q3: Sep, Q4: Dec).

---

## 4. Repository Structure

* [`METHODOLOGY.md`](METHODOLOGY.md) — Official governing rules and index design framework.
* `data/constituents.csv` — Current portfolio list (Tickers, Names, Sector, Base Weight).
* `announcements/` — Quarterly rebalance notices and promotion historical logs.

---

## 5. Documentation & Releases

Official additions, deletions, and quarterly weight adjustments are announced prior to execution under the [GitHub Releases](../../releases) section of this repository.

---
*Arandkei 500 Index. Developed and maintained by Arandkei. All rights reserved.*
