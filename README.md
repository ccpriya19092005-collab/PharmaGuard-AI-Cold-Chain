# PharmaGuard – AI & IoT-Based Pharmaceutical Cold-Chain Monitoring

## Overview
PharmaGuard is an AI and IoT-based prototype designed to monitor pharmaceutical cold-chain transportation, predict potential temperature risks, and verify shipment documentation.

The system combines real-time sensor monitoring, machine learning-based risk prediction, and OCR-based document verification into one dashboard.

## Problem Statement
Temperature-sensitive medicines can be damaged by temperature excursions, humidity, shock, and repeated door openings during transportation.

Traditional monitoring systems mainly generate alerts after a threshold is crossed. Shipment documents are also often checked manually.

PharmaGuard aims to combine predictive monitoring and automated document verification in one system.

## Objectives
- Monitor temperature and humidity using IoT sensors.
- Detect shock and door-opening events.
- Predict potential temperature breaches using machine learning.
- Extract and verify shipment information using OCR.
- Generate a combined shipment health score.
- Display shipment status through a dashboard.

## Proposed Technologies

| Component | Technology |
|---|---|
| Microcontroller | ESP32 |
| Sensors | DHT22, MPU6050, Reed Switch |
| Programming | Python |
| Machine Learning | Scikit-learn |
| OCR | Tesseract |
| Backend | Flask |
| Database | SQLite |
| Dashboard | Streamlit |

## Main Modules
1. IoT-based physical monitoring
2. Predictive risk assessment
3. Shipment document verification
4. Combined health score
5. Interactive dashboard

## Project Status
Currently in the planning and development stage.

## Team
Student project – AI & Data Science Engineering.

## Disclaimer
This is an educational prototype. It is not a certified pharmaceutical monitoring system and is not validated for actual medicine transportation.
