# Digitally Controlled Oscillator (DCO) in 45nm CMOS

A low-power, high-frequency Digitally Controlled Oscillator designed and simulated in **Cadence Virtuoso** using the **GPDK45** (45nm) process design kit. This work extends an existing 90nm reference design and evaluates three delay-element architectures implemented as 3-stage ring oscillators.

![Technology](https://img.shields.io/badge/Technology-45nm%20CMOS-blue)
![Tool](https://img.shields.io/badge/Tool-Cadence%20Virtuoso-red)
![PDK](https://img.shields.io/badge/PDK-GPDK45-green)
![Status](https://img.shields.io/badge/Paper-Submitted%20(IEEE%20Conference)-orange)

---

## Highlights

| Metric | Result |
|---|---|
| Oscillation frequency | ~4.2 GHz |
| Power consumption | < 6 µW |
| Power improvement over reference | ~32.5% |
| Technology node | 45nm CMOS (GPDK45) |
| Topology | 3-stage ring oscillator |

---

## Overview

Digitally Controlled Oscillators are a core building block of All-Digital PLLs, clock generators, and on-chip timing systems, where they replace analog VCOs to improve portability across process nodes and reduce area and power.

This project reimplements and improves upon the 90nm DCO reference by **Pritty and Uma Sharma (2025)**, migrating the design to 45nm and exploring three delay-element (DE) architectures to trade off frequency, tuning range, and power.

## Architectures Explored

| Variant | Description |
|---|---|
| **DE-I** | *Add a one-line description of the first delay-element topology* |
| **DE-II** | *Add a one-line description of the second delay-element topology* |
| **DE-III** | *Add a one-line description of the third delay-element topology* |

Each variant is realised as a 3-stage ring oscillator with digital control over the delay.

## Tools and Environment

- **Cadence Virtuoso**: schematic capture and layout environment
- **Cadence ADE L / ADE XL**: simulation setup and parametric analysis
- **GPDK45**: 45nm generic process design kit
- **Analysis performed**: transient analysis, frequency and power measurement

## Repository Structure

> Adjust to match your actual folders.

```
├── schematics/        # Virtuoso schematic screenshots / exports
├── simulations/       # Waveforms, ADE configurations, results
├── docs/              # Project report and IEEE paper draft
├── results/           # Frequency and power comparison data
└── README.md
```

## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/<your-username>/<repo-name>.git
   ```
2. Open Cadence Virtuoso with the **GPDK45** PDK configured.
3. Import the schematic cells from the `schematics/` directory.
4. Launch ADE L/XL and load the saved simulation states from `simulations/`.
5. Run transient analysis to reproduce the frequency and power figures.

> Note: GPDK45 and Cadence tools are licensed separately and are not distributed in this repository.

## Results

*Add waveform screenshots and a comparison table of DE-I, DE-II and DE-III here.*

| Architecture | Frequency | Power |
|---|---|---|
| DE-I | – | – |
| DE-II | – | – |
| DE-III | – | – |

## Publication

An IEEE conference paper based on this work has been submitted.

*Update with the paper title, conference name and status once available.*

## Team

A six-person student research team, guided by:

- **Dr. V. Govindaraj**: Faculty Guide
- **K. Yogeshwaran**: Faculty Guide

**Team members:**
- Megaraja ([GitHub](https://github.com/<your-username>) · [LinkedIn](https://linkedin.com/in/<your-profile>))
- *Teammate 2*
- *Teammate 3*
- *Teammate 4*
- *Teammate 5*
- *Teammate 6*

**Institution:** KIT – Kalaignarkarunanidhi Institute of Technology, Coimbatore
**Department:** Electronics and Communication Engineering

## Reference

Pritty and Uma Sharma (2025), 90nm Digitally Controlled Oscillator design, the baseline for this work. *(Add full citation.)*

## License

*Choose a license (e.g. MIT) and add a LICENSE file, or state that the repository is for academic reference only.*

## Contact

Feel free to reach out for discussion or feedback:
**Megaraja** · [LinkedIn](https://linkedin.com/in/<your-profile>) · <your-email>
