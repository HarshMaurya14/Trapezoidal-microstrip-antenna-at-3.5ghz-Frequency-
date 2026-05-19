<div align="center">

<h1>📡 Trapezoidal Ring Microstrip Patch Antenna</h1>
<h3>Designed & Simulated at <b>3.5 GHz</b> for 5G Sub-6 GHz Band</h3>

<br/>

![Frequency](https://img.shields.io/badge/Frequency-3.492%20GHz-blue?style=for-the-badge)
![Band](https://img.shields.io/badge/5G%20NR-Band%20n78-brightgreen?style=for-the-badge)
![Simulator](https://img.shields.io/badge/Simulator-CST%20Studio%20Suite-red?style=for-the-badge)
![Substrate](https://img.shields.io/badge/Substrate-FR4%20%7C%20εr%3D4.3-orange?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Fabricated%20✔-success?style=for-the-badge)

<br/>

> **Design and simulation of a trapezoidal ring microstrip patch antenna** operating at **3.492 GHz** for lower-band 5G applications, simulated using **CST Studio Suite** and physically fabricated for real-world validation.

<br/>

</div>

---

## 📌 Table of Contents

- [Overview](#-overview)
- [<span style="color:#0070f3">Design Specifications</span>](#-design-specifications)
- [<span style="color:#0070f3">Antenna Geometry</span>](#-antenna-geometry)
- [Simulation Results](#-simulation-results)
- [S11 Return Loss Plot](#-s11-return-loss-plot)
- [Radiation Pattern](#-radiation-pattern)
- [Fabricated Prototype](#-fabricated-prototype)
- [Files in Repository](#-files-in-repository)
- [Applications](#-applications)
- [Author](#-author)

---

## 🔭 Overview

This project presents the complete design, simulation, and fabrication of a **trapezoidal ring microstrip patch antenna** targeting the **5G NR n78 band (3.4–3.6 GHz)**. The trapezoidal ring geometry is chosen over a conventional rectangular patch to achieve better impedance matching, reduced surface-wave losses, and improved radiation characteristics.

The antenna was designed using the **transmission line model**, where patch dimensions are calculated based on a resonant frequency of **3.5 GHz** and the properties of the FR4 substrate. A **50 Ω microstrip feed line** ensures proper impedance matching.

---

## <span style="color:#0070f3">⚙️ Design Specifications</span>

| Parameter | Value |
|---|---|
| **Resonant Frequency** | 3.492 GHz |
| **Target Band** | 3.4 – 3.6 GHz (5G NR n78) |
| **Substrate** | FR4 |
| **Dielectric Constant (εr)** | 4.3 |
| **Substrate Thickness (h)** | 1.6 mm |
| **Feed Type** | Microstrip Line (50 Ω) |
| **Simulation Tool** | CST Studio Suite |

---

## <span style="color:#0070f3">🖼️ Antenna Geometry</span>

The trapezoidal ring structure replaces the conventional rectangular patch, introducing a gradual impedance variation across the patch surface. This suppresses higher-order modes and widens the impedance bandwidth.

<div align="center">
  <img src="geometry.jpeg" alt="Antenna Geometry" width="600"/>
  <br/>
  <i>Fig 1: Trapezoidal ring microstrip patch antenna design in CST Studio Suite</i>
</div>

---

## 📊 Simulation Results

| Metric | Value |
|---|---|
| **Return Loss (S11)** | −12.664 dB |
| **VSWR** | 1.607 |
| **Directivity** | 6.77 dBi |
| **Resonant Frequency** | 3.492 GHz |

### Key Observations
- ✅ Antenna resonates at **3.492 GHz** — well within the 5G n78 band (3.4–3.6 GHz)
- ✅ Return loss below **−10 dB**, confirming good impedance matching
- ✅ VSWR of **1.607** is within the acceptable range (< 2.0)
- ✅ Broadside radiation pattern — typical and desirable for microstrip patch antennas
- ✅ Directivity of **6.77 dBi** well-suited for 5G and IoT applications

---

## 📉 S11 Return Loss Plot

<div align="center">
  <img src="S11.jpeg" alt="S11 Return Loss" width="600"/>
  <br/>
  <i>Fig 2: S11 Return Loss vs Frequency — resonance at 3.492 GHz with S11 = −12.664 dB</i>
</div>

---

## 🌐 Radiation Pattern

<div align="center">
  <img src="radiation.jpeg" alt="Radiation Pattern" width="600"/>
  <br/>
  <i>Fig 3: Far-field radiation pattern showing broadside directivity of 6.77 dBi</i>
</div>

---

## 🔧 Fabricated Prototype

The antenna design was physically fabricated and tested to validate simulation results against measured performance.

<div align="center">
  <img src="fabricated.jpeg" alt="Fabricated Antenna" width="600"/>
  <br/>
  <i>Fig 4: Fabricated trapezoidal ring microstrip patch antenna prototype</i>
</div>

---

## 📁 Files in Repository

| File | Description |
|---|---|
| `HG (1).cst` | CST Studio Suite project file — full antenna model & simulation setup |
| `micro ewrs.pdf` | Project report with design methodology and detailed results |
| `geometry.jpeg` | Antenna geometry visualization from CST |
| `S11.jpeg` | S11 return loss vs frequency plot |
| `radiation.jpeg` | Far-field radiation pattern |
| `fabricated.jpeg` | Photo of the fabricated physical prototype |

---

## 📡 Applications

- 🌐 **5G NR Sub-6 GHz Communications** (Band n78: 3.4–3.6 GHz)
- 📶 **IoT Devices** requiring compact, low-profile antennas
- 🛜 **Wireless Communication Systems**
- 🔬 **Academic Research** in microstrip antenna design & EM simulation

---

## 👤 Author

**Harsh Maurya**  
🐙 GitHub: [@HarshMaurya14](https://github.com/HarshMaurya14)

---

<div align="center">

⭐ If you found this project useful, consider giving it a star!

</div>
