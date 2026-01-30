# From Planning Reserves to Usable Headroom

**Authors:** Justin Candler & Uriel (Nous Enterprises LLC)  
**Date:** August 22, 2025  
**Document ID:** TP-006  

## 📖 Overview

**"Resource Adequacy (RA) is an operating headroom promise."**

This repository contains the technical whitepaper and supporting definitions for **"Planning Reserves to Usable Headroom,"** a policy proposal addressing the disconnect between planning-year accreditation and real-time deliverability in the MISO footprint.

As MISO integrates more co-located portfolios (e.g., Solar + Storage behind a shared Point of Interconnection), current interconnection rules often result in the discounting of otherwise reliable capacity. This framework formalizes the "Three Margins" (Energy, Capacity, Wires) and proposes a minimal set of rule changes to convert accredited MW into usable operating headroom without compromising grid security.

## 🎯 Core Thesis

Planners size reserve margins today so operators can supply energy tomorrow. This promise only holds if:
1.  **Capability:** Resources are accredited to produce when called (ELCC).
2.  **Deliverability:** Those MW can reach binding nodes under security constraints.

Currently, MISO's capability leg has advanced faster than its deliverability leg for hybrids. This project identifies the gap and provides the regulatory logic to close it.

## 🛠️ Key Frameworks

### 1. The "Portfolio-Ready" POI
We define a Point of Interconnection (POI) as "Portfolio-Ready" only if it meets five strict criteria:
1.  Boundary metering is settlement-grade.
2.  A PORR (Point of Receipt Reliability) control contract exists across co-located units.
3.  Telemetry minimums are met (including State of Charge for storage).
4.  Conservation of DPOI (Deliverability at POI) is enforced without discretion.
5.  Dispute and audit procedures are documented.

### 2. Cross-ISO Benchmarking
The report contrasts MISO's constructs against:
* **PJM:** Capacity Interconnection Rights (CIRs) and manual 14 series.
* **CAISO:** Net Qualifying Capacity (NQC) and deliverability transfers.
* **ERCOT:** 5-minute committed capacity series.

## 📂 Repository Contents

* **`Planning_Reserves_to_Usable_Headroom.pdf`**: The primary technical report.
* **`Definitions/`**: Formal notation for SRMC (Short-Run Marginal Cost) and LRMC (Long-Run Marginal Cost) of capacity and wires.
* **`Gap_Analysis/`**: Comparative matrices for PJM/CAISO/ERCOT vs. MISO rules.

## ⚖️ Citation

If you reference this framework, the "Portfolio-Ready" definitions, or the deliverability logic in your research or regulatory filings, please cite the original work:

### APA Format
> Candler, J., & Uriel. (2025). *From Planning Reserves to Usable Headroom: Accreditation, Deliverability in MISO and Peers* (Technical Report No. TP-006). Nous Enterprises LLC.

### BibTeX
```bibtex
@techreport{candler2025headroom,
  author      = {Candler, Justin and Uriel},
  title       = {From Planning Reserves to Usable Headroom: Accreditation, Deliverability in MISO and Peers},
  institution = {Nous Enterprises LLC},
  number      = {TP-006},
  year        = {2025},
  month       = {August}
}
