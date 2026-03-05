<p align="left">
🇺🇸 <a href="README_eng.md">English</a> |
🇰🇷 <a href="README.md">한국어</a>
</p>

<p align="center">
  <img src="assets/bison_banner.png" width="100%" alt="BISON AI Banner">
</p>

# <img src="assets/Guernsey_icon.png" width="40"> GUERNSEY (BISON Rule Inspection Engine)

**High-Performance Industrial Rule-Based Vision Engine**

BISON Rule Inspection Engine is a high-performance **C++-based rule inspection engine**
designed for industrial machine vision inspection systems.

Core machine vision algorithms such as  
**Subpixel Edge Localization, Hough-based Circle and Line Detection,  
Least-Squares Geometric Fitting, and Precision Metrology**
are integrated into a high-speed inspection pipeline.

This enables **stable real-time inspection performance even in high-speed production environments.**

The engine is designed to run the **same inspection logic** on both

- **Linux-based Edge Vision devices**
- **Windows-based PC Vision systems**

A single inspection engine can support **both Edge Vision devices and PC Vision systems simultaneously.**

---

# 🧠 Industrial Rule Inspection Engine

In industrial inspection environments, the following characteristics are critical:

- Deterministic Inspection  
- Real-Time Processing  
- Stable System Operation  
- High-Speed Image Processing  

The BISON Rule Inspection Engine is designed with a  
**rule inspection architecture optimized for industrial inspection systems.**

Unlike AI-based inspection, rule-based inspection provides several advantages:

- **Predictable inspection results**
- **Faster processing speed**
- **Explainable inspection logic**
- **Long-term stable operation**

Because of these characteristics, rule-based inspection remains  
a **core technology in industrial production inspection systems.**

---

# 📘 Supported Inspection Algorithms

BISON Rule Inspection Engine provides the following core inspection algorithms.

| Category | Algorithms |
|---|---|
| Edge Extraction | Canny Edge Detector, Subpixel Edge Localization |
| Geometric Detection | Hough Circle Transform, Hough Line Transform |
| Geometric Fitting | Least Squares Line Fit, Circle Fit, Arc Fit |
| Blob Analysis | Connected Component Labeling, Blob Feature Extraction |
| Precision Measurement | Distance Measurement, Angle Measurement, Gap / Offset Measurement |
| Shape Matching | Shape-Based Matching, Template Matching (NCC) |
| Pattern Recognition | 1D Barcode Decoding, Pattern Detection |
| Image Enhancement | Adaptive Thresholding, Morphological Filtering |
| Contour Processing | Contour Extraction, Shape Descriptor Analysis |

All algorithms are implemented in **optimized C++ code**
for high-speed industrial inspection environments.

---

# ⚙️ Cross Platform Vision Engine

The BISON inspection engine is designed to run  
the **same inspection logic across multiple platforms.**

| Platform | Support |
|---|---|
| Windows (PC) Vision System | ✔ |
| Linux (Edge) Vision System | ✔ |

This architecture enables the following inspection system configurations:

- Windows PC Vision Inspection System  
- Linux Edge Vision Inspection Device  
- Inline Production Inspection System  
- Smart Factory Vision Inspection System  

A single inspection engine can support **both PC Vision and Edge Vision environments.**

---

# 🔄 High-Speed Inspection Performance

BISON Rule Inspection Engine is designed to provide  
stable inspection performance even in high-speed production environments.

| Inspection Type | Processing Time |
|---|---|
| Edge + Geometry Inspection | ~1–3 ms |
| Barcode Detection | ~2–5 ms |
| Full Inspection Pipeline | ~5–10 ms |

The engine is optimized to maintain **real-time inspection performance**
in real production environments.

---

# 🧩 Inspection Pipeline

```mermaid
flowchart TB

A[Vision Pipeline]

A --> B[Preprocessing]
A --> C[Rule Engine]
A --> D[Feature Extraction]
A --> E[Rule Evaluation]

C --> C1[Edge Detection]
C --> C2[Circle Detection]
C --> C3[Line Detection]
C --> C4[Barcode Recognition]
C --> C5[Etc]
