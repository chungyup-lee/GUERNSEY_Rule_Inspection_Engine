# BISON Rule Inspection Engine

**High‑Performance Industrial Vision Inspection Library**

BISON Rule Inspection Engine is a **high‑speed C++ based rule‑inspection
library** designed for industrial machine vision systems.\
It integrates essential inspection algorithms such as **Edge, Circle,
Line, Measurement, and Barcode recognition** into a single optimized
engine.

The engine is designed for **real‑time production environments**,
enabling reliable and fast inspection for smart factory applications.

------------------------------------------------------------------------

# Why BISON Rule Inspection Engine

Modern manufacturing requires inspection systems that are **fast,
reliable, and scalable across platforms**.

BISON provides a **modular inspection engine** that can be easily
integrated into:

-   PC‑based Vision Inspection Systems
-   Smart Factory Inspection Equipment
-   Edge AI Vision Devices
-   Automated Production Lines

One inspection engine can run consistently across **Windows, Linux, and
Edge AI devices**.

------------------------------------------------------------------------

# Key Advantages

## High‑Speed Industrial Processing

Optimized C++ algorithms enable real‑time inspection performance
suitable for high‑speed production lines.

Typical processing capabilities:

-   Edge Detection
-   Circle Detection
-   Line Detection
-   Geometry Measurement
-   Barcode Recognition

The engine is designed to maintain **stable performance under continuous
industrial operation**.

------------------------------------------------------------------------

## Industrial‑Ready Architecture

The inspection engine is provided as a **standalone DLL / shared
library**, making integration simple and robust.

Benefits include:

-   Easy integration into existing vision systems
-   Modular architecture
-   Reliable industrial operation
-   Scalable inspection pipeline

This design allows manufacturers to upgrade inspection capabilities
**without redesigning the entire system**.

------------------------------------------------------------------------

## Cross‑Platform Vision Engine

The core inspection engine is implemented in **C++**, enabling
deployment across multiple environments.

Supported environments:

  Platform                   Support
  -------------------------- ---------
  Windows Vision Systems     ✔
  Linux Vision Systems       ✔
  Edge AI Devices (Jetson)   ✔

This enables the same inspection algorithm to run on **PC inspection
equipment and Edge AI devices**.

------------------------------------------------------------------------

# System Architecture

Typical inspection pipeline:

Camera\
↓\
Image Acquisition\
↓\
Pre‑Processing\
↓\
**BISON Rule Inspection Engine**\
↓\
Feature Extraction\
↓\
Inspection Decision (OK / NG)\
↓\
PLC / MES / Production System

This modular architecture allows manufacturers to build **scalable
inspection systems for automated production lines**.

------------------------------------------------------------------------

# Supported Inspection Algorithms

  Category             Examples
  -------------------- ----------------------------------
  Edge Detection       Sobel, Canny
  Geometry Detection   Circle Detection, Line Detection
  Measurement          Distance, Angle
  Recognition          Barcode Detection
  Filtering            Threshold, Morphology

Additional inspection modules can be integrated depending on production
requirements.

------------------------------------------------------------------------

# Example Integration

``` cpp
BisonInspectEngine engine;

engine.LoadConfig("inspection_config.json");

InspectionResult result = engine.Run(image);

if(result.isOK)
{
    SendPLC_OK();
}
else
{
    SendPLC_NG();
}
```

The inspection engine can be integrated into **C++, C#, or industrial
vision software systems**.

------------------------------------------------------------------------

# Typical Performance

Typical inspection speed (depending on resolution and hardware):

  Inspection Type            Processing Time
  -------------------------- -----------------
  Edge + Geometry            \~1--3 ms
  Barcode Detection          \~2--5 ms
  Full Inspection Pipeline   \~5--10 ms

The engine is optimized for **real‑time inspection in high‑speed
production environments**.

------------------------------------------------------------------------

# Typical Applications

BISON Rule Inspection Engine is suitable for a wide range of industrial
applications:

-   Automotive component inspection
-   Smart factory inspection systems
-   Inline production inspection
-   Edge AI vision systems
-   High‑speed industrial quality control

------------------------------------------------------------------------

# About BISON Vision Platform

BISON Rule Inspection Engine is a core component of the **BISON Vision
Platform**, a next‑generation industrial vision solution designed for
smart manufacturing.

The platform integrates:

-   Vision Inspection Software
-   AI Inspection Engine
-   Rule‑Based Inspection Engine
-   Edge Vision Devices
-   Industrial Inspection Systems

Together these technologies enable **high‑performance automated
inspection for modern manufacturing**.

------------------------------------------------------------------------

# Contact

**BISON Vision Lab**\
Industrial AI Vision Systems\
Smart Factory Inspection Solutions

For integration or partnership inquiries, please contact the BISON team.
