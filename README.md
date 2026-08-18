🛰️ Mining Surveillance AI
AI-Powered Satellite Monitoring & Early-Warning System for Potential Unauthorized Mining

From Satellite Images to Actionable Mining Triggers.


🚨 The Problem

Unauthorized mining and unplanned excavation can cause:

🌳 Loss of vegetation
🌍 Land degradation
💧 Environmental damage
⛏️ Expansion beyond approved mining boundaries
📉 Loss of natural resources and revenue

Traditional monitoring can be time-consuming and may require repeated field inspections.

Our Question

Can satellite imagery and AI help authorities identify suspicious mining-related land-use changes earlier?

💡 Our Solution

Mining Surveillance AI is a prototype platform that uses multi-temporal Sentinel-2 satellite imagery and AI-assisted geospatial analysis to identify significant land-use changes around mining areas.

Instead of simply declaring an activity "illegal", the system generates an evidence-based trigger for human/official verification.

🔄 Core Workflow
🛰️ Sentinel-2 Satellite Data
            ↓
📅 Multi-Year Image Comparison
       (2021 → 2025)
            ↓
🧹 Image Preprocessing
            ↓
🌱 Spectral / Land-Use Analysis
            ↓
🔍 Change Detection
            ↓
🗺️ Mining Lease Boundary Analysis
            ↓
📍 Monitoring Buffer
            ↓
🤖 AI-Assisted Risk Scoring
            ↓
🚨 Potential Mining Trigger
            ↓
📸 Evidence + Before/After Images
            ↓
👨‍💼 Human / Official Verification
⭐ What Makes It Different?
1. 🛰️ Multi-Year Monitoring

Instead of analyzing a single satellite image, the system compares imagery across multiple years to identify significant changes over time.

2. 🗺️ Boundary-Aware Detection

The system considers the approved mining area and evaluates detected changes relative to the mining boundary.

3. 📍 Monitoring Zone

A configurable monitoring buffer can be applied around the mining boundary to identify suspicious changes near the permitted area.

4. 🚨 Evidence-Based Triggers

The system does not automatically declare an activity illegal.

Instead:

Potential Unauthorized Mining Activity → Trigger → Verification Required

5. 📊 Explainable Risk Score

Each trigger can contain:

Change detected       ✓
Location               ✓
Date comparison        ✓
Boundary relationship  ✓
Change area            ✓
Risk score             ✓
Satellite evidence     ✓

This helps users understand why a trigger was generated.

🏛️ Government Alignment

The prototype is inspired by the satellite-based mining surveillance and trigger-generation approach used in India's Mining Surveillance System (MSS).

The project's goal is not to replace government inspection or legal determination.

Instead, it aims to provide:

AI-assisted evidence → Early warning → Human verification

This makes the system suitable as a prototype for technology-assisted mining surveillance.

📍 Initial Study Area
Bhatadi Open Cast Mine — Chandrapur, Maharashtra 🇮🇳

The initial prototype focuses on a real mining region in Maharashtra.

Approximate study-area center:

Latitude:  20.063
Longitude: 79.274
Satellite Dataset

Sentinel-2 Level-2A

Target period:

2021 → 2025

Images with suitable cloud conditions will be selected for analysis.

🧠 AI & Geospatial Technology
Layer	Technology
Programming	Python
Satellite Data	Sentinel-2
Data Source	Copernicus Data Space
Numerical Computing	NumPy
Image Processing	OpenCV
Raster Processing	Rasterio
Geospatial Analysis	GeoPandas
Geometry	Shapely
Machine Learning	Scikit-learn
Maps	Folium / Leaflet
Visualization	Plotly
Dashboard	Streamlit
Version Control	Git + GitHub
📊 Key Features
🛰️ Sentinel-2 satellite imagery
📅 Multi-temporal monitoring
🗺️ Mining boundary visualization
📍 Monitoring buffer
🔍 Land-use change detection
🌱 Vegetation / bare-land analysis
🤖 AI-assisted risk scoring
🚨 Trigger generation
📸 Before/after satellite evidence
🗺️ Interactive map
📊 Monitoring dashboard
👨‍💼 Human verification workflow
📄 Evidence/report generation
🖥️ Proposed Dashboard
┌─────────────────────────────────────────────┐
│       🛰️ MINING SURVEILLANCE AI             │
├─────────────────────────────────────────────┤
│                                             │
│  📍 Bhatadi, Chandrapur                    │
│                                             │
│  ┌───────────────────────────────────────┐  │
│  │              SATELLITE MAP            │  │
│  │                                       │  │
│  │   🟦 Lease Boundary                   │  │
│  │   🟨 Monitoring Zone                  │  │
│  │   🟥 Detected Change                  │  │
│  └───────────────────────────────────────┘  │
│                                             │
│  Risk Score: 87 / 100                       │
│                                             │
│  Change Detected:        YES                │
│  Boundary Relation:      OUTSIDE            │
│  Confidence:             91%                │
│                                             │
│  ⚠️ POTENTIAL TRIGGER                       │
│                                             │
│  [Before Image] [After Image]               │
│                                             │
│  [Generate Evidence Report]                 │
└─────────────────────────────────────────────┘
📁 Project Structure
mining-surveillance-ai/
│
├── data/
│   ├── raw/
│   ├── processed/
│   └── boundaries/
│
├── notebooks/
│
├── src/
│   ├── preprocessing.py
│   ├── indices.py
│   ├── change_detection.py
│   ├── risk_score.py
│   └── trigger.py
│
├── app/
│   └── dashboard.py
│
├── models/
│
├── outputs/
│   ├── maps/
│   └── reports/
│
├── requirements.txt
├── README.md
└── .gitignore
🚀 Development Roadmap
Phase 1 — Data Collection

Select Maharashtra mining study area

Obtain mining boundary data

Collect Sentinel-2 imagery

Prepare 2021–2025 dataset

Phase 2 — Satellite Processing

Cloud filtering

AOI cropping

Band extraction

NDVI calculation

Bare-land / excavation analysis

Phase 3 — AI & Change Detection

Multi-temporal comparison

Detect significant land-use changes

Boundary comparison

Risk scoring

Trigger generation

Phase 4 — Monitoring Dashboard

Interactive map

Satellite timeline

Trigger dashboard

Before/after evidence

Verification workflow

Report generation

⚠️ Important Disclaimer

This project is a research/hackathon prototype.

A satellite-based change detected by this system does not by itself prove illegal mining.

The system is intended to generate potential activity triggers for further human/official verification.

🎯 Vision

“Transform satellite data into actionable intelligence for faster, smarter and more transparent mining surveillance.”

🏆 Built for Hackathon

Project: Mining Surveillance AI
Domain: Artificial Intelligence + Geospatial Technology + Remote Sensing
Study Area: Maharashtra, India
Satellite: Sentinel-2
