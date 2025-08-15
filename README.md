CMI – Detect Behavior from Sensor Data

This repository contains my work for the Kaggle CMI – Detect Behavior from Sensor Data competition. The goal is to classify human/animal behaviors from multi-modal sensor time-series data.

📌 Competition Overview

Participants are tasked with predicting behavior classes from wearable or embedded sensor streams. The dataset contains multiple sensor channels (e.g., accelerometer, gyroscope, etc.) collected over time, and the objective is to design models that can effectively capture both temporal dependencies and physical motion patterns.

🧠 Approaches

This repo includes two different modeling strategies:

1. Transformer-Based Model

Uses a sequence modeling architecture inspired by NLP transformers.

Captures long-range dependencies in the sensor data without heavy feature engineering.

Focuses on end-to-end learning from raw or lightly processed signals.

2. Two-Branch Physics-Driven Model

Combines:

A deep learning branch for learned representations

A physics-feature branch for engineered motion features (e.g., centripetal acceleration computed as v^2/r, velocity magnitudes, angular velocities, etc.)

Merges learned embeddings with handcrafted physical features to improve generalization.

Emphasis on interpretable features grounded in motion dynamics.
```bash
#!/bin/bash
echo "Hello, GitHub!"
# Your Bash script commands go here
ls -la

