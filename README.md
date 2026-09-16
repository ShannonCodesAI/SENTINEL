# SENTINEL // Multi-Sector Intelligence Console

A dark OSINT-style 3D globe dashboard with real-time data integration.(MIT License).

## Features

- Photorealistic 3D globe (Cesium + Esri satellite imagery)
- Live aircraft tracking (OpenSky Network)
- Live ship positions (AISStream)
- Real-time earthquakes (USGS — keyless)
- Active wildfire detection (NASA FIRMS)
- Real-time traffic + incidents (TomTom)
- Live satellites (Celestrak)
- One-click layer presets (ENVIRONMENTAL / MOBILITY / ORBITAL / GROUND TRUTH)
- Amber/dark military aesthetic with subtle grid overlay
- Floating preset bar (bottom-left) — one click loads 3 layers
- RAM-optimized for 4GB machines (Cesium memory caps + WebGPU detection)

## Acknowledgements

- God's Eye View by Bilawal Sidhu — https://github.com/bilawalsidhu/gods-eye-view (MIT License)
- Z.ai — AI assistance + web search SDK for real-data integrations
- Public data sources: OpenSky, USGS, NASA FIRMS, AISStream, TomTom, Cesium ion, Celestrak

## Setup

### Prerequisites
- Node.js v24+ (use nvm — https://github.com/nvm-sh/nvm)
- 4GB+ RAM

### Install
```bash
git clone https://github.com/ShannonCodesAI/SENTINEL.git
cd SENTINEL
npm install
