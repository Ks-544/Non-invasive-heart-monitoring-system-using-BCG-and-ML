# Non-Invasive Heart Monitoring System using BCG and Machine Learning

## Overview

An ESP32-based non-invasive heart monitoring system that uses an accelerometer to acquire Ballistocardiography (BCG) signals for real-time heart-rate monitoring.

The system applies signal processing and a Random Forest machine-learning model for heart-rate prediction and risk analysis, with results displayed through a real-time dashboard.

## Objectives

- Non-invasive heart-rate monitoring using BCG signals
- Accelerometer-based BCG signal acquisition
- Real-time BCG waveform visualization
- Heart-rate estimation from processed BCG signals
- Random Forest-based heart-rate prediction
- Preliminary risk analysis using extracted parameters

## System Architecture

![System Architecture](images/system-architecture.png)

**Signal Flow:**

Mattress/Chair → Accelerometer → ESP32 → Signal Processing → Heart-Rate Estimation / Random Forest → Real-Time Dashboard

## Hardware

- ESP32
- Accelerometer
- Supporting electronic components
- Mattress/Chair-based sensing setup

## Software & Technologies

- C/C++
- Python
- Arduino IDE
- ESP32
- Signal Processing
- Scikit-learn
- Random Forest
- LTspice
- Real-Time Dashboard

## Signal Processing

The acquired accelerometer signal is processed to reduce noise and extract useful features for heart-rate estimation.

### Processing Pipeline

Raw BCG Signal → Preprocessing → Filtering → Feature Extraction → Heart-Rate Estimation

## Machine Learning

A Random Forest model is used to process extracted signal features for heart-rate prediction and preliminary risk analysis.

### ML Pipeline

Processed BCG Signal → Feature Extraction → Random Forest → Heart-Rate Prediction → Risk Analysis

## Real-Time Dashboard

The dashboard is designed to display:

- Real-time BCG waveform
- Estimated heart rate
- ML-predicted heart rate
- Risk-analysis results
- Monitoring status

### Dashboard Preview

![Dashboard](images/dashboard.png)

## My Contribution

As the Project Group Leader, my contributions include:

- Leading and coordinating the project team
- Circuit design and system simulation
- ESP32 and accelerometer interfacing
- BCG signal processing
- Machine-learning integration
- Real-time system and dashboard integration

## Project Status

🚧 **Ongoing**

The software development, signal processing, ML model training, and dashboard development have been completed. Hardware interfacing and real-time system validation are currently in progress.

## Future Scope

- Improve motion-artifact reduction
- Optimize real-time signal processing
- Validate heart-rate estimation against a reference device
- Improve ML prediction performance
- Develop a compact and portable monitoring system
- Explore wireless/cloud-based remote monitoring

## Disclaimer

This project is an academic/research prototype intended for educational and experimental purposes. It is not intended to replace clinical ECG equipment or professional medical diagnosis.
